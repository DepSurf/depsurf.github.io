# Struct: <code>virtio_balloon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    wait_queue_head_t config_change;
    struct task_struct * thread;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    u32[256] pfns;
    int need_stats_update;
    struct virtio_balloon_stat[6] stats;
    struct notifier_block nb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[7] stats;
    struct notifier_block nb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[7] stats;
    struct notifier_block nb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[7] stats;
    struct notifier_block nb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[7] stats;
    struct notifier_block nb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct notifier_block nb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
    struct notifier_block oom_nb;
    struct virtqueue * reporting_vq;
    struct page_reporting_dev_info pr_dev_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
    struct notifier_block oom_nb;
    struct virtqueue * reporting_vq;
    struct page_reporting_dev_info pr_dev_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
    struct notifier_block oom_nb;
    struct virtqueue * reporting_vq;
    struct page_reporting_dev_info pr_dev_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
    struct notifier_block oom_nb;
    struct virtqueue * reporting_vq;
    struct page_reporting_dev_info pr_dev_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
    struct notifier_block oom_nb;
    struct virtqueue * reporting_vq;
    struct page_reporting_dev_info pr_dev_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
    struct notifier_block oom_nb;
    struct virtqueue * reporting_vq;
    struct page_reporting_dev_info pr_dev_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
    struct notifier_block oom_nb;
    struct virtqueue * reporting_vq;
    struct page_reporting_dev_info pr_dev_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker * shrinker;
    struct notifier_block oom_nb;
    struct virtqueue * reporting_vq;
    struct page_reporting_dev_info pr_dev_info;
    spinlock_t adjustment_lock;
    bool adjustment_signal_pending;
    bool adjustment_in_progress;
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
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
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
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct virtio_balloon {
    struct virtio_device * vdev;
    struct virtqueue * inflate_vq;
    struct virtqueue * deflate_vq;
    struct virtqueue * stats_vq;
    struct virtqueue * free_page_vq;
    struct workqueue_struct * balloon_wq;
    struct work_struct report_free_page_work;
    struct work_struct update_balloon_stats_work;
    struct work_struct update_balloon_size_work;
    spinlock_t stop_update_lock;
    bool stop_update;
    long unsigned int config_read_bitmap;
    struct list_head free_page_list;
    spinlock_t free_page_list_lock;
    long unsigned int num_free_page_blocks;
    u32 cmd_id_received_cache;
    __virtio32 cmd_id_active;
    __virtio32 cmd_id_stop;
    wait_queue_head_t acked;
    unsigned int num_pages;
    struct balloon_dev_info vb_dev_info;
    struct mutex balloon_lock;
    unsigned int num_pfns;
    __virtio32[256] pfns;
    struct virtio_balloon_stat[10] stats;
    struct shrinker shrinker;
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
<code>struct work_struct update_balloon_stats_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct update_balloon_size_work</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t stop_update_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool stop_update</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t config_change</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * thread</code>
</li>
<li>
<b>Field removed. </b>
<code>int need_stats_update</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[256] pfns</code> ➡️ <code>__virtio32[256] pfns</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct virtio_balloon_stat[6] stats</code> ➡️ <code>struct virtio_balloon_stat[7] stats</code>
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct virtio_balloon_stat[7] stats</code> ➡️ <code>struct virtio_balloon_stat[10] stats</code>
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
<code>struct virtqueue * free_page_vq</code>
</li>
<li>
<b>Field added. </b>
<code>struct workqueue_struct * balloon_wq</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct report_free_page_work</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int config_read_bitmap</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head free_page_list</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t free_page_list_lock</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int num_free_page_blocks</code>
</li>
<li>
<b>Field added. </b>
<code>u32 cmd_id_received_cache</code>
</li>
<li>
<b>Field added. </b>
<code>__virtio32 cmd_id_active</code>
</li>
<li>
<b>Field added. </b>
<code>__virtio32 cmd_id_stop</code>
</li>
<li>
<b>Field added. </b>
<code>struct shrinker shrinker</code>
</li>
<li>
<b>Field removed. </b>
<code>struct notifier_block nb</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct notifier_block oom_nb</code>
</li>
<li>
<b>Field added. </b>
<code>struct virtqueue * reporting_vq</code>
</li>
<li>
<b>Field added. </b>
<code>struct page_reporting_dev_info pr_dev_info</code>
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
<code>spinlock_t adjustment_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool adjustment_signal_pending</code>
</li>
<li>
<b>Field added. </b>
<code>bool adjustment_in_progress</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct shrinker shrinker</code> ➡️ <code>struct shrinker * shrinker</code>
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

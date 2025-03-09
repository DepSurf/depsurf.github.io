# Struct: <code>loop_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    unsigned int lo_blocksize;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct mutex lo_ctl_mutex;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    unsigned int lo_blocksize;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct mutex lo_ctl_mutex;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct block_device * lo_device;
    unsigned int lo_blocksize;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct mutex lo_ctl_mutex;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    unsigned int lo_blocksize;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct mutex lo_ctl_mutex;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct mutex lo_ctl_mutex;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct mutex lo_ctl_mutex;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
    struct mutex lo_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    spinlock_t lo_work_lock;
    struct workqueue_struct * workqueue;
    struct work_struct rootcg_work;
    struct list_head rootcg_cmd_list;
    struct list_head idle_worker_list;
    struct rb_root worker_tree;
    struct timer_list timer;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
    struct mutex lo_mutex;
    bool idr_visible;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    char[64] lo_file_name;
    struct file * lo_backing_file;
    struct block_device * lo_device;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    spinlock_t lo_work_lock;
    struct workqueue_struct * workqueue;
    struct work_struct rootcg_work;
    struct list_head rootcg_cmd_list;
    struct list_head idle_worker_list;
    struct rb_root worker_tree;
    struct timer_list timer;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
    struct mutex lo_mutex;
    bool idr_visible;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    char[64] lo_file_name;
    struct file * lo_backing_file;
    struct block_device * lo_device;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    spinlock_t lo_work_lock;
    struct workqueue_struct * workqueue;
    struct work_struct rootcg_work;
    struct list_head rootcg_cmd_list;
    struct list_head idle_worker_list;
    struct rb_root worker_tree;
    struct timer_list timer;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
    struct mutex lo_mutex;
    bool idr_visible;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    char[64] lo_file_name;
    struct file * lo_backing_file;
    struct block_device * lo_device;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    spinlock_t lo_work_lock;
    struct workqueue_struct * workqueue;
    struct work_struct rootcg_work;
    struct list_head rootcg_cmd_list;
    struct list_head idle_worker_list;
    struct rb_root worker_tree;
    struct timer_list timer;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
    struct mutex lo_mutex;
    bool idr_visible;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    char[64] lo_file_name;
    struct file * lo_backing_file;
    struct block_device * lo_device;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    spinlock_t lo_work_lock;
    struct workqueue_struct * workqueue;
    struct work_struct rootcg_work;
    struct list_head rootcg_cmd_list;
    struct list_head idle_worker_list;
    struct rb_root worker_tree;
    struct timer_list timer;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
    struct mutex lo_mutex;
    bool idr_visible;
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
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
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
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct loop_device {
    int lo_number;
    atomic_t lo_refcnt;
    loff_t lo_offset;
    loff_t lo_sizelimit;
    int lo_flags;
    int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer;
    char[64] lo_file_name;
    char[64] lo_crypt_name;
    char[32] lo_encrypt_key;
    int lo_encrypt_key_size;
    struct loop_func_table * lo_encryption;
    __u32[2] lo_init;
    kuid_t lo_key_owner;
    int (*)(struct loop_device *, int, long unsigned int) ioctl;
    struct file * lo_backing_file;
    struct file * lo_backing_virt_file;
    struct block_device * lo_device;
    void * key_data;
    gfp_t old_gfp_mask;
    spinlock_t lo_lock;
    int lo_state;
    struct kthread_worker worker;
    struct task_struct * worker_task;
    bool use_dio;
    bool sysfs_inited;
    struct request_queue * lo_queue;
    struct blk_mq_tag_set tag_set;
    struct gendisk * lo_disk;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct file * lo_backing_virt_file</code>
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
<code>struct file * lo_backing_virt_file</code>
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
<code>unsigned int lo_blocksize</code>
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
<code>bool sysfs_inited</code>
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
<code>struct mutex lo_ctl_mutex</code>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex lo_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>struct file * lo_backing_virt_file</code>
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
<code>struct file * lo_backing_virt_file</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lo_work_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct workqueue_struct * workqueue</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct rootcg_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rootcg_cmd_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head idle_worker_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct rb_root worker_tree</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list timer</code>
</li>
<li>
<b>Field added. </b>
<code>bool idr_visible</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kthread_worker worker</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * worker_task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t lo_refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct loop_device *, int, struct page *, unsigned int, struct page *, unsigned int, int, sector_t) transfer</code>
</li>
<li>
<b>Field removed. </b>
<code>char[64] lo_crypt_name</code>
</li>
<li>
<b>Field removed. </b>
<code>char[32] lo_encrypt_key</code>
</li>
<li>
<b>Field removed. </b>
<code>int lo_encrypt_key_size</code>
</li>
<li>
<b>Field removed. </b>
<code>struct loop_func_table * lo_encryption</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32[2] lo_init</code>
</li>
<li>
<b>Field removed. </b>
<code>kuid_t lo_key_owner</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct loop_device *, int, long unsigned int) ioctl</code>
</li>
<li>
<b>Field removed. </b>
<code>struct file * lo_backing_virt_file</code>
</li>
<li>
<b>Field removed. </b>
<code>void * key_data</code>
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

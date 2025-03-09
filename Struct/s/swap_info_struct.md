# Struct: <code>swap_info_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    struct plist_node avail_list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_info free_cluster_head;
    struct swap_cluster_info free_cluster_tail;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct swap_extent * curr_swap_extent;
    struct swap_extent first_swap_extent;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    struct work_struct discard_work;
    struct swap_cluster_info discard_cluster_head;
    struct swap_cluster_info discard_cluster_tail;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    struct plist_node avail_list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_info free_cluster_head;
    struct swap_cluster_info free_cluster_tail;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct swap_extent * curr_swap_extent;
    struct swap_extent first_swap_extent;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    struct work_struct discard_work;
    struct swap_cluster_info discard_cluster_head;
    struct swap_cluster_info discard_cluster_tail;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    struct plist_node avail_list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct swap_extent * curr_swap_extent;
    struct swap_extent first_swap_extent;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    struct plist_node avail_list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct swap_extent * curr_swap_extent;
    struct swap_extent first_swap_extent;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    struct plist_node[1024] avail_lists;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct swap_extent * curr_swap_extent;
    struct swap_extent first_swap_extent;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    struct plist_node[1024] avail_lists;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct swap_extent * curr_swap_extent;
    struct swap_extent first_swap_extent;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct swap_extent * curr_swap_extent;
    struct swap_extent first_swap_extent;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    unsigned int * cluster_next_cpu;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    unsigned int * cluster_next_cpu;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    unsigned int * cluster_next_cpu;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    struct percpu_ref users;
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    unsigned int * cluster_next_cpu;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    struct completion comp;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    struct percpu_ref users;
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    unsigned int * cluster_next_cpu;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    struct completion comp;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    struct percpu_ref users;
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    unsigned int * cluster_next_cpu;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    struct completion comp;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    struct percpu_ref users;
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    unsigned int * cluster_next_cpu;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    struct completion comp;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    struct percpu_ref users;
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    unsigned int * cluster_next_cpu;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct bdev_handle * bdev_handle;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    struct completion comp;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
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
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
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
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct swap_info_struct {
    long unsigned int flags;
    short int prio;
    struct plist_node list;
    signed char type;
    unsigned int max;
    unsigned char * swap_map;
    struct swap_cluster_info * cluster_info;
    struct swap_cluster_list free_clusters;
    unsigned int lowest_bit;
    unsigned int highest_bit;
    unsigned int pages;
    unsigned int inuse_pages;
    unsigned int cluster_next;
    unsigned int cluster_nr;
    struct percpu_cluster * percpu_cluster;
    struct rb_root swap_extent_root;
    struct block_device * bdev;
    struct file * swap_file;
    unsigned int old_block_size;
    long unsigned int * frontswap_map;
    atomic_t frontswap_pages;
    spinlock_t lock;
    spinlock_t cont_lock;
    struct work_struct discard_work;
    struct swap_cluster_list discard_clusters;
    struct plist_node[0] avail_lists;
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
<b>Field added. </b>
<code>struct swap_cluster_list free_clusters</code>
</li>
<li>
<b>Field added. </b>
<code>struct swap_cluster_list discard_clusters</code>
</li>
<li>
<b>Field removed. </b>
<code>struct swap_cluster_info free_cluster_head</code>
</li>
<li>
<b>Field removed. </b>
<code>struct swap_cluster_info free_cluster_tail</code>
</li>
<li>
<b>Field removed. </b>
<code>struct swap_cluster_info discard_cluster_head</code>
</li>
<li>
<b>Field removed. </b>
<code>struct swap_cluster_info discard_cluster_tail</code>
</li>
</ul>
</details>
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
<code>struct plist_node[1024] avail_lists</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t cont_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct plist_node avail_list</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct plist_node[1024] avail_lists</code> ➡️ <code>struct plist_node[0] avail_lists</code>
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
<code>struct rb_root swap_extent_root</code>
</li>
<li>
<b>Field removed. </b>
<code>struct swap_extent * curr_swap_extent</code>
</li>
<li>
<b>Field removed. </b>
<code>struct swap_extent first_swap_extent</code>
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
<code>unsigned int * cluster_next_cpu</code>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct percpu_ref users</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion comp</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct bdev_handle * bdev_handle</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * frontswap_map</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t frontswap_pages</code>
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

# Struct: <code>block_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    struct list_head bd_inodes;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    sector_t bd_start_sect;
    struct disk_stats * bd_stats;
    long unsigned int bd_stamp;
    bool bd_read_only;
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    struct device bd_device;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct kobject * bd_holder_dir;
    u8 bd_partno;
    unsigned int bd_part_count;
    spinlock_t bd_size_lock;
    struct gendisk * bd_disk;
    struct backing_dev_info * bd_bdi;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
    struct super_block * bd_fsfreeze_sb;
    struct partition_meta_info * bd_meta_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    sector_t bd_start_sect;
    struct disk_stats * bd_stats;
    long unsigned int bd_stamp;
    bool bd_read_only;
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    struct device bd_device;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct kobject * bd_holder_dir;
    u8 bd_partno;
    unsigned int bd_part_count;
    spinlock_t bd_size_lock;
    struct gendisk * bd_disk;
    struct backing_dev_info * bd_bdi;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
    struct super_block * bd_fsfreeze_sb;
    struct partition_meta_info * bd_meta_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    sector_t bd_start_sect;
    struct disk_stats * bd_stats;
    long unsigned int bd_stamp;
    bool bd_read_only;
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    void * bd_claiming;
    struct device bd_device;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct kobject * bd_holder_dir;
    u8 bd_partno;
    spinlock_t bd_size_lock;
    struct gendisk * bd_disk;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
    struct super_block * bd_fsfreeze_sb;
    struct partition_meta_info * bd_meta_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    sector_t bd_start_sect;
    sector_t bd_nr_sectors;
    struct disk_stats * bd_stats;
    long unsigned int bd_stamp;
    bool bd_read_only;
    dev_t bd_dev;
    atomic_t bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    void * bd_claiming;
    struct device bd_device;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct kobject * bd_holder_dir;
    u8 bd_partno;
    spinlock_t bd_size_lock;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
    struct super_block * bd_fsfreeze_sb;
    struct partition_meta_info * bd_meta_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    sector_t bd_start_sect;
    sector_t bd_nr_sectors;
    struct disk_stats * bd_stats;
    long unsigned int bd_stamp;
    bool bd_read_only;
    dev_t bd_dev;
    atomic_t bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    void * bd_claiming;
    struct device bd_device;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct kobject * bd_holder_dir;
    u8 bd_partno;
    spinlock_t bd_size_lock;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
    struct super_block * bd_fsfreeze_sb;
    struct partition_meta_info * bd_meta_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    sector_t bd_start_sect;
    sector_t bd_nr_sectors;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct disk_stats * bd_stats;
    long unsigned int bd_stamp;
    bool bd_read_only;
    u8 bd_partno;
    bool bd_write_holder;
    bool bd_has_submit_bio;
    dev_t bd_dev;
    atomic_t bd_openers;
    spinlock_t bd_size_lock;
    struct inode * bd_inode;
    struct super_block * bd_super;
    void * bd_claiming;
    void * bd_holder;
    const struct blk_holder_ops * bd_holder_ops;
    struct mutex bd_holder_lock;
    int bd_fsfreeze_count;
    int bd_holders;
    struct kobject * bd_holder_dir;
    struct mutex bd_fsfreeze_mutex;
    struct super_block * bd_fsfreeze_sb;
    struct partition_meta_info * bd_meta_info;
    struct device bd_device;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct block_device {
    sector_t bd_start_sect;
    sector_t bd_nr_sectors;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct disk_stats * bd_stats;
    long unsigned int bd_stamp;
    bool bd_read_only;
    u8 bd_partno;
    bool bd_write_holder;
    bool bd_has_submit_bio;
    dev_t bd_dev;
    struct inode * bd_inode;
    atomic_t bd_openers;
    spinlock_t bd_size_lock;
    void * bd_claiming;
    void * bd_holder;
    const struct blk_holder_ops * bd_holder_ops;
    struct mutex bd_holder_lock;
    int bd_holders;
    struct kobject * bd_holder_dir;
    atomic_t bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
    struct partition_meta_info * bd_meta_info;
    bool bd_ro_warned;
    int bd_writers;
    struct device bd_device;
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
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
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
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct block_device {
    dev_t bd_dev;
    int bd_openers;
    struct inode * bd_inode;
    struct super_block * bd_super;
    struct mutex bd_mutex;
    void * bd_claiming;
    void * bd_holder;
    int bd_holders;
    bool bd_write_holder;
    struct list_head bd_holder_disks;
    struct block_device * bd_contains;
    unsigned int bd_block_size;
    u8 bd_partno;
    struct hd_struct * bd_part;
    unsigned int bd_part_count;
    int bd_invalidated;
    struct gendisk * bd_disk;
    struct request_queue * bd_queue;
    struct backing_dev_info * bd_bdi;
    struct list_head bd_list;
    long unsigned int bd_private;
    int bd_fsfreeze_count;
    struct mutex bd_fsfreeze_mutex;
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
<code>struct list_head bd_inodes</code>
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
<code>struct backing_dev_info * bd_bdi</code>
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
<code>u8 bd_partno</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>sector_t bd_start_sect</code>
</li>
<li>
<b>Field added. </b>
<code>struct disk_stats * bd_stats</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int bd_stamp</code>
</li>
<li>
<b>Field added. </b>
<code>bool bd_read_only</code>
</li>
<li>
<b>Field added. </b>
<code>struct device bd_device</code>
</li>
<li>
<b>Field added. </b>
<code>struct kobject * bd_holder_dir</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t bd_size_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct super_block * bd_fsfreeze_sb</code>
</li>
<li>
<b>Field added. </b>
<code>struct partition_meta_info * bd_meta_info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct block_device * bd_contains</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int bd_block_size</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hd_struct * bd_part</code>
</li>
<li>
<b>Field removed. </b>
<code>int bd_invalidated</code>
</li>
<li>
<b>Field removed. </b>
<code>struct request_queue * bd_queue</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head bd_list</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int bd_private</code>
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
<b>Field removed. </b>
<code>struct mutex bd_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head bd_holder_disks</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int bd_part_count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct backing_dev_info * bd_bdi</code>
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
<code>sector_t bd_nr_sectors</code>
</li>
<li>
<b>Field added. </b>
<code>struct request_queue * bd_queue</code>
</li>
<li>
<b>Field type changed. </b>
<code>int bd_openers</code> ➡️ <code>atomic_t bd_openers</code>
</li>
</ul>
</details>
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
<code>bool bd_has_submit_bio</code>
</li>
<li>
<b>Field added. </b>
<code>const struct blk_holder_ops * bd_holder_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex bd_holder_lock</code>
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
<code>bool bd_ro_warned</code>
</li>
<li>
<b>Field added. </b>
<code>int bd_writers</code>
</li>
<li>
<b>Field removed. </b>
<code>struct super_block * bd_super</code>
</li>
<li>
<b>Field removed. </b>
<code>struct super_block * bd_fsfreeze_sb</code>
</li>
<li>
<b>Field type changed. </b>
<code>int bd_fsfreeze_count</code> ➡️ <code>atomic_t bd_fsfreeze_count</code>
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

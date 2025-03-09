# Struct: <code>ext4_inode_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    unsigned int i_reserved_meta_blocks;
    unsigned int i_allocated_meta_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    atomic_t i_ioend_count;
    atomic_t i_unwritten;
    struct work_struct i_rsv_conversion_work;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    struct ext4_crypt_info * i_crypt_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    unsigned int i_reserved_meta_blocks;
    unsigned int i_allocated_meta_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    unsigned int i_reserved_meta_blocks;
    unsigned int i_allocated_meta_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    atomic_t i_prealloc_active;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    struct list_head i_fc_list;
    ext4_lblk_t i_fc_lblk_start;
    ext4_lblk_t i_fc_lblk_len;
    atomic_t i_fc_updates;
    wait_queue_head_t i_fc_wait;
    struct mutex i_fc_lock;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    atomic_t i_prealloc_active;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    struct list_head i_fc_list;
    ext4_lblk_t i_fc_lblk_start;
    ext4_lblk_t i_fc_lblk_len;
    atomic_t i_fc_updates;
    wait_queue_head_t i_fc_wait;
    struct mutex i_fc_lock;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    atomic_t i_prealloc_active;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    unsigned int i_orphan_idx;
    struct list_head i_fc_list;
    ext4_lblk_t i_fc_lblk_start;
    ext4_lblk_t i_fc_lblk_len;
    atomic_t i_fc_updates;
    wait_queue_head_t i_fc_wait;
    struct mutex i_fc_lock;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    atomic_t i_prealloc_active;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    unsigned int i_orphan_idx;
    struct list_head i_fc_dilist;
    struct list_head i_fc_list;
    ext4_lblk_t i_fc_lblk_start;
    ext4_lblk_t i_fc_lblk_len;
    atomic_t i_fc_updates;
    wait_queue_head_t i_fc_wait;
    struct mutex i_fc_lock;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    atomic_t i_prealloc_active;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    unsigned int i_orphan_idx;
    struct list_head i_fc_dilist;
    struct list_head i_fc_list;
    ext4_lblk_t i_fc_lblk_start;
    ext4_lblk_t i_fc_lblk_len;
    atomic_t i_fc_updates;
    wait_queue_head_t i_fc_wait;
    struct mutex i_fc_lock;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    atomic_t i_prealloc_active;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    unsigned int i_orphan_idx;
    struct list_head i_fc_dilist;
    struct list_head i_fc_list;
    ext4_lblk_t i_fc_lblk_start;
    ext4_lblk_t i_fc_lblk_len;
    atomic_t i_fc_updates;
    wait_queue_head_t i_fc_wait;
    struct mutex i_fc_lock;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    atomic_t i_prealloc_active;
    struct rb_root i_prealloc_node;
    rwlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    unsigned int i_orphan_idx;
    struct list_head i_fc_dilist;
    struct list_head i_fc_list;
    ext4_lblk_t i_fc_lblk_start;
    ext4_lblk_t i_fc_lblk_len;
    atomic_t i_fc_updates;
    wait_queue_head_t i_fc_wait;
    struct mutex i_fc_lock;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    atomic_t i_prealloc_active;
    struct rb_root i_prealloc_node;
    rwlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
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
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_state_flags;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
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
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ext4_inode_info {
    __le32[15] i_data;
    __u32 i_dtime;
    ext4_fsblk_t i_file_acl;
    ext4_group_t i_block_group;
    ext4_lblk_t i_dir_start_lookup;
    long unsigned int i_flags;
    struct rw_semaphore xattr_sem;
    struct list_head i_orphan;
    loff_t i_disksize;
    struct rw_semaphore i_data_sem;
    struct rw_semaphore i_mmap_sem;
    struct inode vfs_inode;
    struct jbd2_inode * jinode;
    spinlock_t i_raw_lock;
    struct timespec64 i_crtime;
    struct list_head i_prealloc_list;
    spinlock_t i_prealloc_lock;
    struct ext4_es_tree i_es_tree;
    rwlock_t i_es_lock;
    struct list_head i_es_list;
    unsigned int i_es_all_nr;
    unsigned int i_es_shk_nr;
    ext4_lblk_t i_es_shrink_lblk;
    ext4_group_t i_last_alloc_group;
    unsigned int i_reserved_data_blocks;
    ext4_lblk_t i_da_metadata_calc_last_lblock;
    int i_da_metadata_calc_len;
    struct ext4_pending_tree i_pending_tree;
    __u16 i_extra_isize;
    u16 i_inline_off;
    u16 i_inline_size;
    qsize_t i_reserved_quota;
    spinlock_t i_completed_io_lock;
    struct list_head i_rsv_conversion_list;
    struct work_struct i_rsv_conversion_work;
    atomic_t i_unwritten;
    spinlock_t i_block_reservation_lock;
    tid_t i_sync_tid;
    tid_t i_datasync_tid;
    struct dquot *[3] i_dquot;
    __u32 i_csum_seed;
    kprojid_t i_projid;
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
<code>struct rw_semaphore i_mmap_sem</code>
</li>
<li>
<b>Field added. </b>
<code>kprojid_t i_projid</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t i_ioend_count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ext4_crypt_info * i_crypt_info</code>
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
<b>Field removed. </b>
<code>unsigned int i_reserved_meta_blocks</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int i_allocated_meta_blocks</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ext4_pending_tree i_pending_tree</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct timespec i_crtime</code> ➡️ <code>struct timespec64 i_crtime</code>
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
<code>atomic_t i_prealloc_active</code>
</li>
<li>
<b>Field removed. </b>
<code>ext4_lblk_t i_da_metadata_calc_last_lblock</code>
</li>
<li>
<b>Field removed. </b>
<code>int i_da_metadata_calc_len</code>
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
<code>struct list_head i_fc_list</code>
</li>
<li>
<b>Field added. </b>
<code>ext4_lblk_t i_fc_lblk_start</code>
</li>
<li>
<b>Field added. </b>
<code>ext4_lblk_t i_fc_lblk_len</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t i_fc_updates</code>
</li>
<li>
<b>Field added. </b>
<code>wait_queue_head_t i_fc_wait</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex i_fc_lock</code>
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
<code>unsigned int i_orphan_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rw_semaphore i_mmap_sem</code>
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
<code>struct list_head i_fc_dilist</code>
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
<code>struct rb_root i_prealloc_node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head i_prealloc_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>spinlock_t i_prealloc_lock</code> ➡️ <code>rwlock_t i_prealloc_lock</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int i_state_flags</code>
</li>
</ul>
</details>
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

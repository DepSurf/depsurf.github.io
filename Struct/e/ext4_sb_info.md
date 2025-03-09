# Struct: <code>ext4_sb_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    spinlock_t s_next_gen_lock;
    u32 s_next_generation;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_resize_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[2] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct rb_root system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_mb_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    spinlock_t s_next_gen_lock;
    u32 s_next_generation;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_resize_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct rb_root system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_mb_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_journal_flag_rwsem;
    u8[5] key_prefix;
    u8 key_prefix_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    spinlock_t s_next_gen_lock;
    u32 s_next_generation;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_resize_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct rb_root system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_mb_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_journal_flag_rwsem;
    u8[5] key_prefix;
    u8 key_prefix_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    spinlock_t s_next_gen_lock;
    u32 s_next_generation;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct rb_root system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_journal_flag_rwsem;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct rb_root system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_journal_flag_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct rb_root system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_journal_flag_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct rb_root system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_journal_flag_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct rb_root system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_journal_flag_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_mb_max_inode_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct fscrypt_dummy_context s_dummy_enc_ctx;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
    errseq_t s_bdev_wb_err;
    spinlock_t s_bdev_wb_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    long unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct percpu_counter s_sra_exceeded_retry_limit;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * s_journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * s_system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_mb_max_inode_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    unsigned int s_mb_prefetch;
    unsigned int s_mb_prefetch_limit;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    atomic_t s_warning_count;
    atomic_t s_msg_count;
    struct fscrypt_dummy_policy s_dummy_enc_policy;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
    errseq_t s_bdev_wb_err;
    spinlock_t s_bdev_wb_lock;
    spinlock_t s_error_lock;
    int s_add_error_count;
    int s_first_error_code;
    __u32 s_first_error_line;
    __u32 s_first_error_ino;
    __u64 s_first_error_block;
    const char * s_first_error_func;
    time64_t s_first_error_time;
    int s_last_error_code;
    __u32 s_last_error_line;
    __u32 s_last_error_ino;
    __u64 s_last_error_block;
    const char * s_last_error_func;
    time64_t s_last_error_time;
    struct work_struct s_error_work;
    atomic_t s_fc_subtid;
    atomic_t s_fc_ineligible_updates;
    struct list_head[2] s_fc_q;
    struct list_head[2] s_fc_dentry_q;
    unsigned int s_fc_bytes;
    spinlock_t s_fc_lock;
    struct buffer_head * s_fc_bh;
    struct ext4_fc_stats s_fc_stats;
    u64 s_fc_avg_commit_time;
    struct ext4_fc_replay_state s_fc_replay_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    long unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct percpu_counter s_sra_exceeded_retry_limit;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct buffer_head * s_mmp_bh;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * s_journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * s_system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    struct rb_root s_mb_avg_fragment_size_root;
    rwlock_t s_mb_rb_lock;
    struct list_head * s_mb_largest_free_orders;
    rwlock_t * s_mb_largest_free_orders_locks;
    long unsigned int s_stripe;
    unsigned int s_mb_max_linear_groups;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_mb_max_inode_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    unsigned int s_mb_prefetch;
    unsigned int s_mb_prefetch_limit;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_groups_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    atomic_t s_bal_cr0_bad_suggestions;
    atomic_t s_bal_cr1_bad_suggestions;
    atomic64_t[4] s_bal_cX_groups_considered;
    atomic64_t[4] s_bal_cX_hits;
    atomic64_t[4] s_bal_cX_failed;
    atomic_t s_mb_buddies_generated;
    atomic64_t s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    atomic_t s_warning_count;
    atomic_t s_msg_count;
    struct fscrypt_dummy_policy s_dummy_enc_policy;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
    errseq_t s_bdev_wb_err;
    spinlock_t s_bdev_wb_lock;
    spinlock_t s_error_lock;
    int s_add_error_count;
    int s_first_error_code;
    __u32 s_first_error_line;
    __u32 s_first_error_ino;
    __u64 s_first_error_block;
    const char * s_first_error_func;
    time64_t s_first_error_time;
    int s_last_error_code;
    __u32 s_last_error_line;
    __u32 s_last_error_ino;
    __u64 s_last_error_block;
    const char * s_last_error_func;
    time64_t s_last_error_time;
    struct work_struct s_error_work;
    atomic_t s_fc_subtid;
    atomic_t s_fc_ineligible_updates;
    struct list_head[2] s_fc_q;
    struct list_head[2] s_fc_dentry_q;
    unsigned int s_fc_bytes;
    spinlock_t s_fc_lock;
    struct buffer_head * s_fc_bh;
    struct ext4_fc_stats s_fc_stats;
    u64 s_fc_avg_commit_time;
    struct ext4_fc_replay_state s_fc_replay_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    long unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct percpu_counter s_sra_exceeded_retry_limit;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct buffer_head * s_mmp_bh;
    struct journal_s * s_journal;
    long unsigned int s_ext4_flags;
    struct mutex s_orphan_lock;
    struct list_head s_orphan;
    struct ext4_orphan_info s_orphan_info;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * s_journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * s_system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    struct list_head s_discard_list;
    struct work_struct s_discard_work;
    atomic_t s_retry_alloc_pending;
    struct rb_root s_mb_avg_fragment_size_root;
    rwlock_t s_mb_rb_lock;
    struct list_head * s_mb_largest_free_orders;
    rwlock_t * s_mb_largest_free_orders_locks;
    long unsigned int s_stripe;
    unsigned int s_mb_max_linear_groups;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_mb_max_inode_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    unsigned int s_mb_prefetch;
    unsigned int s_mb_prefetch_limit;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_groups_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    atomic_t s_bal_cr0_bad_suggestions;
    atomic_t s_bal_cr1_bad_suggestions;
    atomic64_t[4] s_bal_cX_groups_considered;
    atomic64_t[4] s_bal_cX_hits;
    atomic64_t[4] s_bal_cX_failed;
    atomic_t s_mb_buddies_generated;
    atomic64_t s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ext4_journal_trigger[1] s_journal_triggers;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    atomic_t s_warning_count;
    atomic_t s_msg_count;
    struct fscrypt_dummy_policy s_dummy_enc_policy;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
    errseq_t s_bdev_wb_err;
    spinlock_t s_bdev_wb_lock;
    spinlock_t s_error_lock;
    int s_add_error_count;
    int s_first_error_code;
    __u32 s_first_error_line;
    __u32 s_first_error_ino;
    __u64 s_first_error_block;
    const char * s_first_error_func;
    time64_t s_first_error_time;
    int s_last_error_code;
    __u32 s_last_error_line;
    __u32 s_last_error_ino;
    __u64 s_last_error_block;
    const char * s_last_error_func;
    time64_t s_last_error_time;
    struct work_struct s_error_work;
    atomic_t s_fc_subtid;
    struct list_head[2] s_fc_q;
    struct list_head[2] s_fc_dentry_q;
    unsigned int s_fc_bytes;
    spinlock_t s_fc_lock;
    struct buffer_head * s_fc_bh;
    struct ext4_fc_stats s_fc_stats;
    tid_t s_fc_ineligible_tid;
    struct ext4_fc_replay_state s_fc_replay_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    long unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct percpu_counter s_sra_exceeded_retry_limit;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct buffer_head * s_mmp_bh;
    struct journal_s * s_journal;
    long unsigned int s_ext4_flags;
    struct mutex s_orphan_lock;
    struct list_head s_orphan;
    struct ext4_orphan_info s_orphan_info;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * s_journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * s_system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    struct list_head s_discard_list;
    struct work_struct s_discard_work;
    atomic_t s_retry_alloc_pending;
    struct rb_root s_mb_avg_fragment_size_root;
    rwlock_t s_mb_rb_lock;
    struct list_head * s_mb_largest_free_orders;
    rwlock_t * s_mb_largest_free_orders_locks;
    long unsigned int s_stripe;
    unsigned int s_mb_max_linear_groups;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_mb_max_inode_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    unsigned int s_mb_prefetch;
    unsigned int s_mb_prefetch_limit;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_groups_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    atomic_t s_bal_cr0_bad_suggestions;
    atomic_t s_bal_cr1_bad_suggestions;
    atomic64_t[4] s_bal_cX_groups_considered;
    atomic64_t[4] s_bal_cX_hits;
    atomic64_t[4] s_bal_cX_failed;
    atomic_t s_mb_buddies_generated;
    atomic64_t s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    long unsigned int s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ext4_journal_trigger[1] s_journal_triggers;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    atomic_t s_warning_count;
    atomic_t s_msg_count;
    struct fscrypt_dummy_policy s_dummy_enc_policy;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
    u64 s_dax_part_off;
    errseq_t s_bdev_wb_err;
    spinlock_t s_bdev_wb_lock;
    spinlock_t s_error_lock;
    int s_add_error_count;
    int s_first_error_code;
    __u32 s_first_error_line;
    __u32 s_first_error_ino;
    __u64 s_first_error_block;
    const char * s_first_error_func;
    time64_t s_first_error_time;
    int s_last_error_code;
    __u32 s_last_error_line;
    __u32 s_last_error_ino;
    __u64 s_last_error_block;
    const char * s_last_error_func;
    time64_t s_last_error_time;
    struct work_struct s_error_work;
    atomic_t s_fc_subtid;
    struct list_head[2] s_fc_q;
    struct list_head[2] s_fc_dentry_q;
    unsigned int s_fc_bytes;
    spinlock_t s_fc_lock;
    struct buffer_head * s_fc_bh;
    struct ext4_fc_stats s_fc_stats;
    tid_t s_fc_ineligible_tid;
    struct ext4_fc_replay_state s_fc_replay_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    long unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    unsigned int s_def_mount_opt2;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct percpu_counter s_sra_exceeded_retry_limit;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct buffer_head * s_mmp_bh;
    struct journal_s * s_journal;
    long unsigned int s_ext4_flags;
    struct mutex s_orphan_lock;
    struct list_head s_orphan;
    struct ext4_orphan_info s_orphan_info;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * s_journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * s_system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    struct list_head s_discard_list;
    struct work_struct s_discard_work;
    atomic_t s_retry_alloc_pending;
    struct list_head * s_mb_avg_fragment_size;
    rwlock_t * s_mb_avg_fragment_size_locks;
    struct list_head * s_mb_largest_free_orders;
    rwlock_t * s_mb_largest_free_orders_locks;
    long unsigned int s_stripe;
    unsigned int s_mb_max_linear_groups;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_mb_max_inode_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    unsigned int s_mb_prefetch;
    unsigned int s_mb_prefetch_limit;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_groups_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    atomic_t s_bal_cr0_bad_suggestions;
    atomic_t s_bal_cr1_bad_suggestions;
    atomic64_t[4] s_bal_cX_groups_considered;
    atomic64_t[4] s_bal_cX_hits;
    atomic64_t[4] s_bal_cX_failed;
    atomic_t s_mb_buddies_generated;
    atomic64_t s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    long unsigned int s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ext4_journal_trigger[1] s_journal_triggers;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    atomic_t s_warning_count;
    atomic_t s_msg_count;
    struct fscrypt_dummy_policy s_dummy_enc_policy;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
    u64 s_dax_part_off;
    errseq_t s_bdev_wb_err;
    spinlock_t s_bdev_wb_lock;
    spinlock_t s_error_lock;
    int s_add_error_count;
    int s_first_error_code;
    __u32 s_first_error_line;
    __u32 s_first_error_ino;
    __u64 s_first_error_block;
    const char * s_first_error_func;
    time64_t s_first_error_time;
    int s_last_error_code;
    __u32 s_last_error_line;
    __u32 s_last_error_ino;
    __u64 s_last_error_block;
    const char * s_last_error_func;
    time64_t s_last_error_time;
    struct work_struct s_error_work;
    atomic_t s_fc_subtid;
    struct list_head[2] s_fc_q;
    struct list_head[2] s_fc_dentry_q;
    unsigned int s_fc_bytes;
    spinlock_t s_fc_lock;
    struct buffer_head * s_fc_bh;
    struct ext4_fc_stats s_fc_stats;
    tid_t s_fc_ineligible_tid;
    struct ext4_fc_replay_state s_fc_replay_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    long unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    unsigned int s_def_mount_opt2;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct percpu_counter s_sra_exceeded_retry_limit;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct buffer_head * s_mmp_bh;
    struct journal_s * s_journal;
    long unsigned int s_ext4_flags;
    struct mutex s_orphan_lock;
    struct list_head s_orphan;
    struct ext4_orphan_info s_orphan_info;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * s_journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * s_system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    struct list_head s_discard_list;
    struct work_struct s_discard_work;
    atomic_t s_retry_alloc_pending;
    struct list_head * s_mb_avg_fragment_size;
    rwlock_t * s_mb_avg_fragment_size_locks;
    struct list_head * s_mb_largest_free_orders;
    rwlock_t * s_mb_largest_free_orders_locks;
    long unsigned int s_stripe;
    unsigned int s_mb_max_linear_groups;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    unsigned int s_mb_prefetch;
    unsigned int s_mb_prefetch_limit;
    unsigned int s_mb_best_avail_max_trim_order;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t[5] s_bal_cX_ex_scanned;
    atomic_t s_bal_groups_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_len_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    atomic_t s_bal_p2_aligned_bad_suggestions;
    atomic_t s_bal_goal_fast_bad_suggestions;
    atomic_t s_bal_best_avail_bad_suggestions;
    atomic64_t[5] s_bal_cX_groups_considered;
    atomic64_t[5] s_bal_cX_hits;
    atomic64_t[5] s_bal_cX_failed;
    atomic_t s_mb_buddies_generated;
    atomic64_t s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    long unsigned int s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ext4_journal_trigger[1] s_journal_triggers;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    atomic_t s_warning_count;
    atomic_t s_msg_count;
    struct fscrypt_dummy_policy s_dummy_enc_policy;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
    u64 s_dax_part_off;
    errseq_t s_bdev_wb_err;
    spinlock_t s_bdev_wb_lock;
    spinlock_t s_error_lock;
    int s_add_error_count;
    int s_first_error_code;
    __u32 s_first_error_line;
    __u32 s_first_error_ino;
    __u64 s_first_error_block;
    const char * s_first_error_func;
    time64_t s_first_error_time;
    int s_last_error_code;
    __u32 s_last_error_line;
    __u32 s_last_error_ino;
    __u64 s_last_error_block;
    const char * s_last_error_func;
    time64_t s_last_error_time;
    struct work_struct s_error_work;
    atomic_t s_fc_subtid;
    struct list_head[2] s_fc_q;
    struct list_head[2] s_fc_dentry_q;
    unsigned int s_fc_bytes;
    spinlock_t s_fc_lock;
    struct buffer_head * s_fc_bh;
    struct ext4_fc_stats s_fc_stats;
    tid_t s_fc_ineligible_tid;
    struct ext4_fc_replay_state s_fc_replay_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    long unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    unsigned int s_def_mount_opt2;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct percpu_counter s_sra_exceeded_retry_limit;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct buffer_head * s_mmp_bh;
    struct journal_s * s_journal;
    long unsigned int s_ext4_flags;
    struct mutex s_orphan_lock;
    struct list_head s_orphan;
    struct ext4_orphan_info s_orphan_info;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct bdev_handle * s_journal_bdev_handle;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * s_system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head[2] s_freed_data_list;
    struct list_head s_discard_list;
    struct work_struct s_discard_work;
    atomic_t s_retry_alloc_pending;
    struct list_head * s_mb_avg_fragment_size;
    rwlock_t * s_mb_avg_fragment_size_locks;
    struct list_head * s_mb_largest_free_orders;
    rwlock_t * s_mb_largest_free_orders_locks;
    long unsigned int s_stripe;
    unsigned int s_mb_max_linear_groups;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    unsigned int s_mb_prefetch;
    unsigned int s_mb_prefetch_limit;
    unsigned int s_mb_best_avail_max_trim_order;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t[5] s_bal_cX_ex_scanned;
    atomic_t s_bal_groups_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_len_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    atomic_t s_bal_p2_aligned_bad_suggestions;
    atomic_t s_bal_goal_fast_bad_suggestions;
    atomic_t s_bal_best_avail_bad_suggestions;
    atomic64_t[5] s_bal_cX_groups_considered;
    atomic64_t[5] s_bal_cX_hits;
    atomic64_t[5] s_bal_cX_failed;
    atomic_t s_mb_buddies_generated;
    atomic64_t s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    long unsigned int s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker * s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ext4_journal_trigger[1] s_journal_triggers;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    atomic_t s_warning_count;
    atomic_t s_msg_count;
    struct fscrypt_dummy_policy s_dummy_enc_policy;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
    u64 s_dax_part_off;
    errseq_t s_bdev_wb_err;
    spinlock_t s_bdev_wb_lock;
    spinlock_t s_error_lock;
    int s_add_error_count;
    int s_first_error_code;
    __u32 s_first_error_line;
    __u32 s_first_error_ino;
    __u64 s_first_error_block;
    const char * s_first_error_func;
    time64_t s_first_error_time;
    int s_last_error_code;
    __u32 s_last_error_line;
    __u32 s_last_error_ino;
    __u64 s_last_error_block;
    const char * s_last_error_func;
    time64_t s_last_error_time;
    struct work_struct s_sb_upd_work;
    atomic_t s_fc_subtid;
    struct list_head[2] s_fc_q;
    struct list_head[2] s_fc_dentry_q;
    unsigned int s_fc_bytes;
    spinlock_t s_fc_lock;
    struct buffer_head * s_fc_bh;
    struct ext4_fc_stats s_fc_stats;
    tid_t s_fc_ineligible_tid;
    struct ext4_fc_replay_state s_fc_replay_state;
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
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
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
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ext4_sb_info {
    long unsigned int s_desc_size;
    long unsigned int s_inodes_per_block;
    long unsigned int s_blocks_per_group;
    long unsigned int s_clusters_per_group;
    long unsigned int s_inodes_per_group;
    long unsigned int s_itb_per_group;
    long unsigned int s_gdb_count;
    long unsigned int s_desc_per_block;
    ext4_group_t s_groups_count;
    ext4_group_t s_blockfile_groups;
    long unsigned int s_overhead;
    unsigned int s_cluster_ratio;
    unsigned int s_cluster_bits;
    loff_t s_bitmap_maxbytes;
    struct buffer_head * s_sbh;
    struct ext4_super_block * s_es;
    struct buffer_head * * s_group_desc;
    unsigned int s_mount_opt;
    unsigned int s_mount_opt2;
    unsigned int s_mount_flags;
    unsigned int s_def_mount_opt;
    ext4_fsblk_t s_sb_block;
    atomic64_t s_resv_clusters;
    kuid_t s_resuid;
    kgid_t s_resgid;
    short unsigned int s_mount_state;
    short unsigned int s_pad;
    int s_addr_per_block_bits;
    int s_desc_per_block_bits;
    int s_inode_size;
    int s_first_ino;
    unsigned int s_inode_readahead_blks;
    unsigned int s_inode_goal;
    u32[4] s_hash_seed;
    int s_def_hash_version;
    int s_hash_unsigned;
    struct percpu_counter s_freeclusters_counter;
    struct percpu_counter s_freeinodes_counter;
    struct percpu_counter s_dirs_counter;
    struct percpu_counter s_dirtyclusters_counter;
    struct blockgroup_lock * s_blockgroup_lock;
    struct proc_dir_entry * s_proc;
    struct kobject s_kobj;
    struct completion s_kobj_unregister;
    struct super_block * s_sb;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct journal_s * s_journal;
    struct list_head s_orphan;
    struct mutex s_orphan_lock;
    long unsigned int s_ext4_flags;
    long unsigned int s_commit_interval;
    u32 s_max_batch_time;
    u32 s_min_batch_time;
    struct block_device * journal_bdev;
    char *[3] s_qf_names;
    int s_jquota_fmt;
    unsigned int s_want_extra_isize;
    struct ext4_system_blocks * system_blks;
    struct ext4_group_info * * * s_group_info;
    struct inode * s_buddy_cache;
    spinlock_t s_md_lock;
    short unsigned int * s_mb_offsets;
    unsigned int * s_mb_maxs;
    unsigned int s_group_info_size;
    unsigned int s_mb_free_pending;
    struct list_head s_freed_data_list;
    long unsigned int s_stripe;
    unsigned int s_mb_stream_request;
    unsigned int s_mb_max_to_scan;
    unsigned int s_mb_min_to_scan;
    unsigned int s_mb_stats;
    unsigned int s_mb_order2_reqs;
    unsigned int s_mb_group_prealloc;
    unsigned int s_max_dir_size_kb;
    long unsigned int s_mb_last_group;
    long unsigned int s_mb_last_start;
    atomic_t s_bal_reqs;
    atomic_t s_bal_success;
    atomic_t s_bal_allocated;
    atomic_t s_bal_ex_scanned;
    atomic_t s_bal_goals;
    atomic_t s_bal_breaks;
    atomic_t s_bal_2orders;
    spinlock_t s_bal_lock;
    long unsigned int s_mb_buddies_generated;
    long long unsigned int s_mb_generation_time;
    atomic_t s_mb_lost_chunks;
    atomic_t s_mb_preallocated;
    atomic_t s_mb_discarded;
    atomic_t s_lock_busy;
    struct ext4_locality_group * s_locality_groups;
    long unsigned int s_sectors_written_start;
    u64 s_kbytes_written;
    unsigned int s_extent_max_zeroout_kb;
    unsigned int s_log_groups_per_flex;
    struct flex_groups * * s_flex_groups;
    ext4_group_t s_flex_groups_allocated;
    struct workqueue_struct * rsv_conversion_wq;
    struct timer_list s_err_report;
    struct ext4_li_request * s_li_request;
    unsigned int s_li_wait_mult;
    struct task_struct * s_mmp_tsk;
    atomic_t s_last_trim_minblks;
    struct crypto_shash * s_chksum_driver;
    __u32 s_csum_seed;
    struct shrinker s_es_shrinker;
    struct list_head s_es_list;
    long int s_es_nr_inode;
    struct ext4_es_stats s_es_stats;
    struct mb_cache * s_ea_block_cache;
    struct mb_cache * s_ea_inode_cache;
    spinlock_t s_es_lock;
    struct ratelimit_state s_err_ratelimit_state;
    struct ratelimit_state s_warning_ratelimit_state;
    struct ratelimit_state s_msg_ratelimit_state;
    struct percpu_rw_semaphore s_writepages_rwsem;
    struct dax_device * s_daxdev;
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
<code>unsigned int s_mb_free_pending</code>
</li>
<li>
<b>Field added. </b>
<code>struct percpu_rw_semaphore s_journal_flag_rwsem</code>
</li>
<li>
<b>Field added. </b>
<code>u8[5] key_prefix</code>
</li>
<li>
<b>Field added. </b>
<code>u8 key_prefix_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>char *[2] s_qf_names</code> ➡️ <code>char *[3] s_qf_names</code>
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
<code>long unsigned int s_ext4_flags</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head s_freed_data_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct mb_cache * s_ea_block_cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct mb_cache * s_ea_inode_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int s_resize_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mb_cache * s_mb_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[5] key_prefix</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 key_prefix_size</code>
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
<code>struct dax_device * s_daxdev</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t s_next_gen_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 s_next_generation</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct unicode_map * s_encoding</code>
</li>
<li>
<b>Field added. </b>
<code>__u16 s_encoding_flags</code>
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
<code>struct percpu_rw_semaphore s_writepages_rwsem</code>
</li>
<li>
<b>Field removed. </b>
<code>struct percpu_rw_semaphore s_journal_flag_rwsem</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rb_root system_blks</code> ➡️ <code>struct ext4_system_blocks * system_blks</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct flex_groups * s_flex_groups</code> ➡️ <code>struct flex_groups * * s_flex_groups</code>
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
<code>unsigned int s_mb_max_inode_prealloc</code>
</li>
<li>
<b>Field added. </b>
<code>struct fscrypt_dummy_context s_dummy_enc_ctx</code>
</li>
<li>
<b>Field added. </b>
<code>errseq_t s_bdev_wb_err</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t s_bdev_wb_lock</code>
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
<code>struct percpu_counter s_sra_exceeded_retry_limit</code>
</li>
<li>
<b>Field added. </b>
<code>struct block_device * s_journal_bdev</code>
</li>
<li>
<b>Field added. </b>
<code>struct ext4_system_blocks * s_system_blks</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int s_mb_prefetch</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int s_mb_prefetch_limit</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_warning_count</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_msg_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct fscrypt_dummy_policy s_dummy_enc_policy</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t s_error_lock</code>
</li>
<li>
<b>Field added. </b>
<code>int s_add_error_count</code>
</li>
<li>
<b>Field added. </b>
<code>int s_first_error_code</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 s_first_error_line</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 s_first_error_ino</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 s_first_error_block</code>
</li>
<li>
<b>Field added. </b>
<code>const char * s_first_error_func</code>
</li>
<li>
<b>Field added. </b>
<code>time64_t s_first_error_time</code>
</li>
<li>
<b>Field added. </b>
<code>int s_last_error_code</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 s_last_error_line</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 s_last_error_ino</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 s_last_error_block</code>
</li>
<li>
<b>Field added. </b>
<code>const char * s_last_error_func</code>
</li>
<li>
<b>Field added. </b>
<code>time64_t s_last_error_time</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct s_error_work</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_fc_subtid</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_fc_ineligible_updates</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head[2] s_fc_q</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head[2] s_fc_dentry_q</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int s_fc_bytes</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t s_fc_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct buffer_head * s_fc_bh</code>
</li>
<li>
<b>Field added. </b>
<code>struct ext4_fc_stats s_fc_stats</code>
</li>
<li>
<b>Field added. </b>
<code>u64 s_fc_avg_commit_time</code>
</li>
<li>
<b>Field added. </b>
<code>struct ext4_fc_replay_state s_fc_replay_state</code>
</li>
<li>
<b>Field removed. </b>
<code>struct unicode_map * s_encoding</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 s_encoding_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct block_device * journal_bdev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ext4_system_blocks * system_blks</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fscrypt_dummy_context s_dummy_enc_ctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int s_mount_flags</code> ➡️ <code>long unsigned int s_mount_flags</code>
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
<code>struct buffer_head * s_mmp_bh</code>
</li>
<li>
<b>Field added. </b>
<code>struct rb_root s_mb_avg_fragment_size_root</code>
</li>
<li>
<b>Field added. </b>
<code>rwlock_t s_mb_rb_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head * s_mb_largest_free_orders</code>
</li>
<li>
<b>Field added. </b>
<code>rwlock_t * s_mb_largest_free_orders_locks</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int s_mb_max_linear_groups</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_bal_groups_scanned</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_bal_cr0_bad_suggestions</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_bal_cr1_bad_suggestions</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t[4] s_bal_cX_groups_considered</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t[4] s_bal_cX_hits</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t[4] s_bal_cX_failed</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t s_bal_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int s_mb_buddies_generated</code> ➡️ <code>atomic_t s_mb_buddies_generated</code>
</li>
<li>
<b>Field type changed. </b>
<code>long long unsigned int s_mb_generation_time</code> ➡️ <code>atomic64_t s_mb_generation_time</code>
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
<code>struct ext4_orphan_info s_orphan_info</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head s_discard_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct s_discard_work</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_retry_alloc_pending</code>
</li>
<li>
<b>Field added. </b>
<code>struct ext4_journal_trigger[1] s_journal_triggers</code>
</li>
<li>
<b>Field added. </b>
<code>tid_t s_fc_ineligible_tid</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t s_fc_ineligible_updates</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 s_fc_avg_commit_time</code>
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
<code>u64 s_dax_part_off</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t s_last_trim_minblks</code> ➡️ <code>long unsigned int s_last_trim_minblks</code>
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
<code>unsigned int s_def_mount_opt2</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head * s_mb_avg_fragment_size</code>
</li>
<li>
<b>Field added. </b>
<code>rwlock_t * s_mb_avg_fragment_size_locks</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_root s_mb_avg_fragment_size_root</code>
</li>
<li>
<b>Field removed. </b>
<code>rwlock_t s_mb_rb_lock</code>
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
<code>unsigned int s_mb_best_avail_max_trim_order</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t[5] s_bal_cX_ex_scanned</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_bal_len_goals</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_bal_p2_aligned_bad_suggestions</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_bal_goal_fast_bad_suggestions</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t s_bal_best_avail_bad_suggestions</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int s_mb_max_inode_prealloc</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t s_bal_cr0_bad_suggestions</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t s_bal_cr1_bad_suggestions</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic64_t[4] s_bal_cX_groups_considered</code> ➡️ <code>atomic64_t[5] s_bal_cX_groups_considered</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic64_t[4] s_bal_cX_hits</code> ➡️ <code>atomic64_t[5] s_bal_cX_hits</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic64_t[4] s_bal_cX_failed</code> ➡️ <code>atomic64_t[5] s_bal_cX_failed</code>
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
<code>struct bdev_handle * s_journal_bdev_handle</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct s_sb_upd_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct block_device * s_journal_bdev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct s_error_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head s_freed_data_list</code> ➡️ <code>struct list_head[2] s_freed_data_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct shrinker s_es_shrinker</code> ➡️ <code>struct shrinker * s_es_shrinker</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct unicode_map * s_encoding</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 s_encoding_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

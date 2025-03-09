# Struct: <code>journal_s</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct mutex j_abort_mutex;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    int j_revoke_records_per_block;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct mutex j_abort_mutex;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    wait_queue_head_t j_fc_wait;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    long unsigned int j_fc_first;
    long unsigned int j_fc_off;
    long unsigned int j_fc_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_total_len;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    int j_revoke_records_per_block;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    struct buffer_head * * j_fc_wbuf;
    int j_wbufsize;
    int j_fc_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    int (*)(struct jbd2_inode *) j_submit_inode_data_buffers;
    int (*)(struct jbd2_inode *) j_finish_inode_data_buffers;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
    void (*)(struct journal_s *, int) j_fc_cleanup_callback;
    int (*)(struct journal_s *, struct buffer_head *, enum passtype, int, tid_t) j_fc_replay_callback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct mutex j_abort_mutex;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    wait_queue_head_t j_fc_wait;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    long unsigned int j_fc_first;
    long unsigned int j_fc_off;
    long unsigned int j_fc_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_total_len;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    int j_revoke_records_per_block;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    struct buffer_head * * j_fc_wbuf;
    int j_wbufsize;
    int j_fc_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    int (*)(struct jbd2_inode *) j_submit_inode_data_buffers;
    int (*)(struct jbd2_inode *) j_finish_inode_data_buffers;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
    void (*)(struct journal_s *, int) j_fc_cleanup_callback;
    int (*)(struct journal_s *, struct buffer_head *, enum passtype, int, tid_t) j_fc_replay_callback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    long unsigned int j_atomic_flags;
    int j_errno;
    struct mutex j_abort_mutex;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    wait_queue_head_t j_fc_wait;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    struct shrinker j_shrinker;
    struct percpu_counter j_checkpoint_jh_count;
    transaction_t * j_shrink_transaction;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    long unsigned int j_fc_first;
    long unsigned int j_fc_off;
    long unsigned int j_fc_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_total_len;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    int j_revoke_records_per_block;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    struct buffer_head * * j_fc_wbuf;
    int j_wbufsize;
    int j_fc_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    int (*)(struct jbd2_inode *) j_submit_inode_data_buffers;
    int (*)(struct jbd2_inode *) j_finish_inode_data_buffers;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
    void (*)(struct journal_s *, int, tid_t) j_fc_cleanup_callback;
    int (*)(struct journal_s *, struct buffer_head *, enum passtype, int, tid_t) j_fc_replay_callback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    long unsigned int j_atomic_flags;
    int j_errno;
    struct mutex j_abort_mutex;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    wait_queue_head_t j_fc_wait;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    struct shrinker j_shrinker;
    struct percpu_counter j_checkpoint_jh_count;
    transaction_t * j_shrink_transaction;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    long unsigned int j_fc_first;
    long unsigned int j_fc_off;
    long unsigned int j_fc_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_total_len;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    int j_revoke_records_per_block;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    struct buffer_head * * j_fc_wbuf;
    int j_wbufsize;
    int j_fc_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    int (*)(struct jbd2_inode *) j_submit_inode_data_buffers;
    int (*)(struct jbd2_inode *) j_finish_inode_data_buffers;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
    void (*)(struct journal_s *, int, tid_t) j_fc_cleanup_callback;
    int (*)(struct journal_s *, struct buffer_head *, enum passtype, int, tid_t) j_fc_replay_callback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    long unsigned int j_atomic_flags;
    int j_errno;
    struct mutex j_abort_mutex;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    wait_queue_head_t j_fc_wait;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    struct shrinker j_shrinker;
    struct percpu_counter j_checkpoint_jh_count;
    transaction_t * j_shrink_transaction;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    long unsigned int j_fc_first;
    long unsigned int j_fc_off;
    long unsigned int j_fc_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_total_len;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    int j_revoke_records_per_block;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    struct buffer_head * * j_fc_wbuf;
    int j_wbufsize;
    int j_fc_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    int (*)(struct jbd2_inode *) j_submit_inode_data_buffers;
    int (*)(struct jbd2_inode *) j_finish_inode_data_buffers;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
    void (*)(struct journal_s *, int, tid_t) j_fc_cleanup_callback;
    int (*)(struct journal_s *, struct buffer_head *, enum passtype, int, tid_t) j_fc_replay_callback;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    long unsigned int j_atomic_flags;
    int j_errno;
    struct mutex j_abort_mutex;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    wait_queue_head_t j_fc_wait;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    struct shrinker j_shrinker;
    struct percpu_counter j_checkpoint_jh_count;
    transaction_t * j_shrink_transaction;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    long unsigned int j_fc_first;
    long unsigned int j_fc_off;
    long unsigned int j_fc_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_total_len;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    int j_revoke_records_per_block;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    struct buffer_head * * j_fc_wbuf;
    int j_wbufsize;
    int j_fc_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    int (*)(struct jbd2_inode *) j_submit_inode_data_buffers;
    int (*)(struct jbd2_inode *) j_finish_inode_data_buffers;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
    void (*)(struct journal_s *, int, tid_t) j_fc_cleanup_callback;
    int (*)(struct journal_s *, struct buffer_head *, enum passtype, int, tid_t) j_fc_replay_callback;
    int (*)(struct journal_s *, sector_t *) j_bmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct mutex j_abort_mutex;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    wait_queue_head_t j_fc_wait;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    struct shrinker * j_shrinker;
    struct percpu_counter j_checkpoint_jh_count;
    transaction_t * j_shrink_transaction;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    long unsigned int j_fc_first;
    long unsigned int j_fc_off;
    long unsigned int j_fc_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    errseq_t j_fs_dev_wb_err;
    unsigned int j_total_len;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    int j_revoke_records_per_block;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    struct buffer_head * * j_fc_wbuf;
    int j_wbufsize;
    int j_fc_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    int (*)(struct jbd2_inode *) j_submit_inode_data_buffers;
    int (*)(struct jbd2_inode *) j_finish_inode_data_buffers;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
    void (*)(struct journal_s *, int, tid_t) j_fc_cleanup_callback;
    int (*)(struct journal_s *, struct buffer_head *, enum passtype, int, tid_t) j_fc_replay_callback;
    int (*)(struct journal_s *, sector_t *) j_bmap;
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
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
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
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct journal_s {
    long unsigned int j_flags;
    int j_errno;
    struct buffer_head * j_sb_buffer;
    journal_superblock_t * j_superblock;
    int j_format_version;
    rwlock_t j_state_lock;
    int j_barrier_count;
    struct mutex j_barrier;
    transaction_t * j_running_transaction;
    transaction_t * j_committing_transaction;
    transaction_t * j_checkpoint_transactions;
    wait_queue_head_t j_wait_transaction_locked;
    wait_queue_head_t j_wait_done_commit;
    wait_queue_head_t j_wait_commit;
    wait_queue_head_t j_wait_updates;
    wait_queue_head_t j_wait_reserved;
    struct mutex j_checkpoint_mutex;
    struct buffer_head *[64] j_chkpt_bhs;
    long unsigned int j_head;
    long unsigned int j_tail;
    long unsigned int j_free;
    long unsigned int j_first;
    long unsigned int j_last;
    struct block_device * j_dev;
    int j_blocksize;
    long long unsigned int j_blk_offset;
    char[56] j_devname;
    struct block_device * j_fs_dev;
    unsigned int j_maxlen;
    atomic_t j_reserved_credits;
    spinlock_t j_list_lock;
    struct inode * j_inode;
    tid_t j_tail_sequence;
    tid_t j_transaction_sequence;
    tid_t j_commit_sequence;
    tid_t j_commit_request;
    __u8[16] j_uuid;
    struct task_struct * j_task;
    int j_max_transaction_buffers;
    long unsigned int j_commit_interval;
    struct timer_list j_commit_timer;
    spinlock_t j_revoke_lock;
    struct jbd2_revoke_table_s * j_revoke;
    struct jbd2_revoke_table_s *[2] j_revoke_table;
    struct buffer_head * * j_wbuf;
    int j_wbufsize;
    pid_t j_last_sync_writer;
    u64 j_average_commit_time;
    u32 j_min_batch_time;
    u32 j_max_batch_time;
    void (*)(journal_t *, transaction_t *) j_commit_callback;
    spinlock_t j_history_lock;
    struct proc_dir_entry * j_proc_entry;
    struct transaction_stats_s j_stats;
    unsigned int j_failed_commit;
    void * j_private;
    struct crypto_shash * j_chksum_driver;
    __u32 j_csum_seed;
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex j_abort_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>int j_revoke_records_per_block</code>
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
<code>wait_queue_head_t j_fc_wait</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int j_fc_first</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int j_fc_off</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int j_fc_last</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int j_total_len</code>
</li>
<li>
<b>Field added. </b>
<code>struct buffer_head * * j_fc_wbuf</code>
</li>
<li>
<b>Field added. </b>
<code>int j_fc_wbufsize</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct jbd2_inode *) j_submit_inode_data_buffers</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct jbd2_inode *) j_finish_inode_data_buffers</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct journal_s *, int) j_fc_cleanup_callback</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct journal_s *, struct buffer_head *, enum passtype, int, tid_t) j_fc_replay_callback</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int j_maxlen</code>
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
<code>long unsigned int j_atomic_flags</code>
</li>
<li>
<b>Field added. </b>
<code>struct shrinker j_shrinker</code>
</li>
<li>
<b>Field added. </b>
<code>struct percpu_counter j_checkpoint_jh_count</code>
</li>
<li>
<b>Field added. </b>
<code>transaction_t * j_shrink_transaction</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct journal_s *, int) j_fc_cleanup_callback</code> ➡️ <code>void (*)(struct journal_s *, int, tid_t) j_fc_cleanup_callback</code>
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
<code>int (*)(struct journal_s *, sector_t *) j_bmap</code>
</li>
<li>
<b>Field removed. </b>
<code>int j_format_version</code>
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
<code>errseq_t j_fs_dev_wb_err</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int j_atomic_flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct shrinker j_shrinker</code> ➡️ <code>struct shrinker * j_shrinker</code>
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

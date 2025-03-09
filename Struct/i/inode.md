# Struct: <code>inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec i_atime;
    struct timespec i_mtime;
    struct timespec i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    unsigned int i_blkbits;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct mutex i_mutex;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    u64 i_version;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct hlist_head i_fsnotify_marks;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec i_atime;
    struct timespec i_mtime;
    struct timespec i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    unsigned int i_blkbits;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    u64 i_version;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct hlist_head i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec i_atime;
    struct timespec i_mtime;
    struct timespec i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    unsigned int i_blkbits;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    u64 i_version;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct hlist_head i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec i_atime;
    struct timespec i_mtime;
    struct timespec i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    unsigned int i_blkbits;
    enum rw_hint i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    u64 i_version;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec i_atime;
    struct timespec i_mtime;
    struct timespec i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    unsigned int i_blkbits;
    enum rw_hint i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    u64 i_version;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    unsigned int i_blkbits;
    enum rw_hint i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 __i_atime;
    struct timespec64 __i_mtime;
    struct timespec64 __i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_inode_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
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
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    seqcount_t i_size_seqcount;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
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
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inode {
    umode_t i_mode;
    short unsigned int i_opflags;
    kuid_t i_uid;
    kgid_t i_gid;
    unsigned int i_flags;
    struct posix_acl * i_acl;
    struct posix_acl * i_default_acl;
    const struct inode_operations * i_op;
    struct super_block * i_sb;
    struct address_space * i_mapping;
    void * i_security;
    long unsigned int i_ino;
    const unsigned int i_nlink;
    unsigned int __i_nlink;
    dev_t i_rdev;
    loff_t i_size;
    struct timespec64 i_atime;
    struct timespec64 i_mtime;
    struct timespec64 i_ctime;
    spinlock_t i_lock;
    short unsigned int i_bytes;
    u8 i_blkbits;
    u8 i_write_hint;
    blkcnt_t i_blocks;
    long unsigned int i_state;
    struct rw_semaphore i_rwsem;
    long unsigned int dirtied_when;
    long unsigned int dirtied_time_when;
    struct hlist_node i_hash;
    struct list_head i_io_list;
    struct bdi_writeback * i_wb;
    int i_wb_frn_winner;
    u16 i_wb_frn_avg_time;
    u16 i_wb_frn_history;
    struct list_head i_lru;
    struct list_head i_sb_list;
    struct list_head i_wb_list;
    struct hlist_head i_dentry;
    struct callback_head i_rcu;
    atomic64_t i_version;
    atomic64_t i_sequence;
    atomic_t i_count;
    atomic_t i_dio_count;
    atomic_t i_writecount;
    atomic_t i_readcount;
    const struct file_operations * i_fop;
    void (*)(struct inode *) free_inode;
    struct file_lock_context * i_flctx;
    struct address_space i_data;
    struct list_head i_devices;
    struct pipe_inode_info * i_pipe;
    struct block_device * i_bdev;
    struct cdev * i_cdev;
    char * i_link;
    unsigned int i_dir_seq;
    __u32 i_generation;
    __u32 i_fsnotify_mask;
    struct fsnotify_mark_connector * i_fsnotify_marks;
    struct fscrypt_info * i_crypt_info;
    struct fsverity_info * i_verity_info;
    void * i_private;
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
<code>struct rw_semaphore i_rwsem</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head i_wb_list</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int i_dir_seq</code>
</li>
<li>
<b>Field added. </b>
<code>struct fscrypt_info * i_crypt_info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex i_mutex</code>
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
<code>enum rw_hint i_write_hint</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hlist_head i_fsnotify_marks</code> ➡️ <code>struct fsnotify_mark_connector * i_fsnotify_marks</code>
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
<b>Field type changed. </b>
<code>struct timespec i_atime</code> ➡️ <code>struct timespec64 i_atime</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct timespec i_mtime</code> ➡️ <code>struct timespec64 i_mtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct timespec i_ctime</code> ➡️ <code>struct timespec64 i_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 i_version</code> ➡️ <code>atomic64_t i_version</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int i_blkbits</code> ➡️ <code>u8 i_blkbits</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum rw_hint i_write_hint</code> ➡️ <code>u8 i_write_hint</code>
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
<code>void (*)(struct inode *) free_inode</code>
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
<code>atomic64_t i_sequence</code>
</li>
<li>
<b>Field added. </b>
<code>struct fsverity_info * i_verity_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct block_device * i_bdev</code>
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
<code>struct timespec64 __i_atime</code>
</li>
<li>
<b>Field added. </b>
<code>struct timespec64 __i_mtime</code>
</li>
<li>
<b>Field added. </b>
<code>struct timespec64 __i_ctime</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timespec64 i_atime</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timespec64 i_mtime</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timespec64 i_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fscrypt_info * i_crypt_info</code> ➡️ <code>struct fscrypt_inode_info * i_crypt_info</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>seqcount_t i_size_seqcount</code>
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

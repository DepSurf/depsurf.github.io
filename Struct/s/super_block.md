# Struct: <code>super_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    struct hlist_bl_head s_anon;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    char[32] s_id;
    u8[16] s_uuid;
    void * s_fs_info;
    unsigned int s_max_links;
    fmode_t s_mode;
    u32 s_time_gran;
    struct mutex s_vfs_rename_mutex;
    char * s_subtype;
    char * s_options;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct hlist_bl_head s_anon;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    char[32] s_id;
    u8[16] s_uuid;
    void * s_fs_info;
    unsigned int s_max_links;
    fmode_t s_mode;
    u32 s_time_gran;
    struct mutex s_vfs_rename_mutex;
    char * s_subtype;
    char * s_options;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct hlist_bl_head s_anon;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    char[32] s_id;
    u8[16] s_uuid;
    void * s_fs_info;
    unsigned int s_max_links;
    fmode_t s_mode;
    u32 s_time_gran;
    struct mutex s_vfs_rename_mutex;
    char * s_subtype;
    char * s_options;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct hlist_bl_head s_anon;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    char[32] s_id;
    uuid_t s_uuid;
    void * s_fs_info;
    unsigned int s_max_links;
    fmode_t s_mode;
    u32 s_time_gran;
    struct mutex s_vfs_rename_mutex;
    char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct hlist_bl_head s_anon;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    char[32] s_id;
    uuid_t s_uuid;
    void * s_fs_info;
    unsigned int s_max_links;
    fmode_t s_mode;
    u32 s_time_gran;
    struct mutex s_vfs_rename_mutex;
    char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    char[32] s_id;
    uuid_t s_uuid;
    void * s_fs_info;
    unsigned int s_max_links;
    fmode_t s_mode;
    u32 s_time_gran;
    struct mutex s_vfs_rename_mutex;
    char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    errseq_t s_wb_err;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    errseq_t s_wb_err;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    errseq_t s_wb_err;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_connectors;
    int s_readonly_remount;
    errseq_t s_wb_err;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_connectors;
    int s_readonly_remount;
    errseq_t s_wb_err;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct fscrypt_keyring * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_connectors;
    int s_readonly_remount;
    errseq_t s_wb_err;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct fscrypt_keyring * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_connectors;
    int s_readonly_remount;
    errseq_t s_wb_err;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct fscrypt_keyring * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct unicode_map * s_encoding;
    __u16 s_encoding_flags;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct bdev_handle * s_bdev_handle;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    struct shrinker * s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_connectors;
    int s_readonly_remount;
    errseq_t s_wb_err;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
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
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
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
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct super_block {
    struct list_head s_list;
    dev_t s_dev;
    unsigned char s_blocksize_bits;
    long unsigned int s_blocksize;
    loff_t s_maxbytes;
    struct file_system_type * s_type;
    const struct super_operations * s_op;
    const struct dquot_operations * dq_op;
    const struct quotactl_ops * s_qcop;
    const struct export_operations * s_export_op;
    long unsigned int s_flags;
    long unsigned int s_iflags;
    long unsigned int s_magic;
    struct dentry * s_root;
    struct rw_semaphore s_umount;
    int s_count;
    atomic_t s_active;
    void * s_security;
    const struct xattr_handler * * s_xattr;
    const struct fscrypt_operations * s_cop;
    struct key * s_master_keys;
    const struct fsverity_operations * s_vop;
    struct hlist_bl_head s_roots;
    struct list_head s_mounts;
    struct block_device * s_bdev;
    struct backing_dev_info * s_bdi;
    struct mtd_info * s_mtd;
    struct hlist_node s_instances;
    unsigned int s_quota_types;
    struct quota_info s_dquot;
    struct sb_writers s_writers;
    void * s_fs_info;
    u32 s_time_gran;
    time64_t s_time_min;
    time64_t s_time_max;
    __u32 s_fsnotify_mask;
    struct fsnotify_mark_connector * s_fsnotify_marks;
    char[32] s_id;
    uuid_t s_uuid;
    unsigned int s_max_links;
    fmode_t s_mode;
    struct mutex s_vfs_rename_mutex;
    const char * s_subtype;
    const struct dentry_operations * s_d_op;
    int cleancache_poolid;
    struct shrinker s_shrink;
    atomic_long_t s_remove_count;
    atomic_long_t s_fsnotify_inode_refs;
    int s_readonly_remount;
    struct workqueue_struct * s_dio_done_wq;
    struct hlist_head s_pins;
    struct user_namespace * s_user_ns;
    struct list_lru s_dentry_lru;
    struct list_lru s_inode_lru;
    struct callback_head rcu;
    struct work_struct destroy_work;
    struct mutex s_sync_lock;
    int s_stack_depth;
    spinlock_t s_inode_list_lock;
    struct list_head s_inodes;
    spinlock_t s_inode_wblist_lock;
    struct list_head s_inodes_wb;
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
<code>const struct fscrypt_operations * s_cop</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t s_inode_wblist_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head s_inodes_wb</code>
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
<code>char * s_options</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[16] s_uuid</code> ➡️ <code>uuid_t s_uuid</code>
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
<code>struct hlist_bl_head s_roots</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_bl_head s_anon</code>
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
<code>__u32 s_fsnotify_mask</code>
</li>
<li>
<b>Field added. </b>
<code>struct fsnotify_mark_connector * s_fsnotify_marks</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t s_fsnotify_inode_refs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>char * s_subtype</code> ➡️ <code>const char * s_subtype</code>
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
<code>struct key * s_master_keys</code>
</li>
<li>
<b>Field added. </b>
<code>const struct fsverity_operations * s_vop</code>
</li>
<li>
<b>Field added. </b>
<code>time64_t s_time_min</code>
</li>
<li>
<b>Field added. </b>
<code>time64_t s_time_max</code>
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
<code>errseq_t s_wb_err</code>
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_long_t s_fsnotify_connectors</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t s_fsnotify_inode_refs</code>
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
<code>int cleancache_poolid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct key * s_master_keys</code> ➡️ <code>struct fscrypt_keyring * s_master_keys</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>fmode_t s_mode</code>
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
<code>struct bdev_handle * s_bdev_handle</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct xattr_handler * * s_xattr</code> ➡️ <code>const const struct xattr_handler * * s_xattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct shrinker s_shrink</code> ➡️ <code>struct shrinker * s_shrink</code>
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
<b>Field type changed. </b>
<code>struct mtd_info * s_mtd</code> ➡️ <code>struct mtd_info * s_mtd</code>
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

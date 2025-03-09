# Struct: <code>fuse_conn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    atomic_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int flags;
    unsigned int max_read;
    unsigned int max_write;
    struct fuse_iqueue iq;
    u64 khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    wait_queue_head_t reserved_req_waitq;
    unsigned int connected;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int bdi_initialized;
    unsigned int writeback_cache;
    unsigned int no_open;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    atomic_t num_waiting;
    unsigned int minor;
    struct backing_dev_info bdi;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    struct fuse_req * destroy_req;
    u64 attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    atomic_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int flags;
    unsigned int max_read;
    unsigned int max_write;
    struct fuse_iqueue iq;
    u64 khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    wait_queue_head_t reserved_req_waitq;
    unsigned int connected;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int bdi_initialized;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int no_open;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    atomic_t num_waiting;
    unsigned int minor;
    struct backing_dev_info bdi;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    struct fuse_req * destroy_req;
    u64 attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    atomic_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    struct fuse_iqueue iq;
    u64 khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    wait_queue_head_t reserved_req_waitq;
    unsigned int connected;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int bdi_initialized;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int no_open;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    atomic_t num_waiting;
    unsigned int minor;
    struct backing_dev_info bdi;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    struct fuse_req * destroy_req;
    u64 attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    struct fuse_iqueue iq;
    u64 khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    wait_queue_head_t reserved_req_waitq;
    unsigned int connected;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int no_open;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    struct fuse_req * destroy_req;
    u64 attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    struct fuse_iqueue iq;
    u64 khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    wait_queue_head_t reserved_req_waitq;
    unsigned int connected;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int no_open;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    struct fuse_req * destroy_req;
    u64 attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    struct fuse_iqueue iq;
    u64 khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    wait_queue_head_t reserved_req_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int no_open;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    struct fuse_req * destroy_req;
    u64 attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    u64 khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    wait_queue_head_t reserved_req_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    struct fuse_req * destroy_req;
    u64 attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    wait_queue_head_t reserved_req_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    struct fuse_req * destroy_req;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int legacy_opts_show;
    unsigned int handle_killpriv_v2;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int auto_submounts;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct rw_semaphore killsb;
    struct list_head devices;
    struct fuse_conn_dax * dax;
    struct list_head mounts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    unsigned int max_pages_limit;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int legacy_opts_show;
    unsigned int handle_killpriv_v2;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int setxattr_ext;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int auto_submounts;
    unsigned int sync_fs;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct rw_semaphore killsb;
    struct list_head devices;
    struct fuse_conn_dax * dax;
    struct list_head mounts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    unsigned int max_pages_limit;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int legacy_opts_show;
    unsigned int handle_killpriv_v2;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int setxattr_ext;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int auto_submounts;
    unsigned int sync_fs;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct rw_semaphore killsb;
    struct list_head devices;
    struct fuse_conn_dax * dax;
    struct list_head mounts;
    struct fuse_sync_bucket * curr_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    unsigned int max_pages_limit;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int legacy_opts_show;
    unsigned int handle_killpriv_v2;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int setxattr_ext;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int auto_submounts;
    unsigned int sync_fs;
    unsigned int init_security;
    unsigned int inode_dax;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct rw_semaphore killsb;
    struct list_head devices;
    enum fuse_dax_mode dax_mode;
    struct fuse_conn_dax * dax;
    struct list_head mounts;
    struct fuse_sync_bucket * curr_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    unsigned int max_pages_limit;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int legacy_opts_show;
    unsigned int handle_killpriv_v2;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int setxattr_ext;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int auto_submounts;
    unsigned int sync_fs;
    unsigned int init_security;
    unsigned int inode_dax;
    unsigned int no_tmpfile;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct rw_semaphore killsb;
    struct list_head devices;
    enum fuse_dax_mode dax_mode;
    struct fuse_conn_dax * dax;
    struct list_head mounts;
    struct fuse_sync_bucket * curr_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    unsigned int max_pages_limit;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int legacy_opts_show;
    unsigned int handle_killpriv_v2;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int setxattr_ext;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int auto_submounts;
    unsigned int sync_fs;
    unsigned int init_security;
    unsigned int create_supp_group;
    unsigned int inode_dax;
    unsigned int no_tmpfile;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct rw_semaphore killsb;
    struct list_head devices;
    enum fuse_dax_mode dax_mode;
    struct fuse_conn_dax * dax;
    struct list_head mounts;
    struct fuse_sync_bucket * curr_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    unsigned int max_pages_limit;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int legacy_opts_show;
    unsigned int handle_killpriv_v2;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int setxattr_ext;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int auto_submounts;
    unsigned int sync_fs;
    unsigned int init_security;
    unsigned int create_supp_group;
    unsigned int inode_dax;
    unsigned int no_tmpfile;
    unsigned int direct_io_allow_mmap;
    unsigned int no_statx;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct rw_semaphore killsb;
    struct list_head devices;
    enum fuse_dax_mode dax_mode;
    struct fuse_conn_dax * dax;
    struct list_head mounts;
    struct fuse_sync_bucket * curr_bucket;
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
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
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
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fuse_conn {
    spinlock_t lock;
    refcount_t count;
    atomic_t dev_count;
    struct callback_head rcu;
    kuid_t user_id;
    kgid_t group_id;
    struct pid_namespace * pid_ns;
    struct user_namespace * user_ns;
    unsigned int max_read;
    unsigned int max_write;
    unsigned int max_pages;
    struct fuse_iqueue iq;
    atomic64_t khctr;
    struct rb_root polled_files;
    unsigned int max_background;
    unsigned int congestion_threshold;
    unsigned int num_background;
    unsigned int active_background;
    struct list_head bg_queue;
    spinlock_t bg_lock;
    int initialized;
    int blocked;
    wait_queue_head_t blocked_waitq;
    unsigned int connected;
    bool aborted;
    unsigned int conn_error;
    unsigned int conn_init;
    unsigned int async_read;
    unsigned int abort_err;
    unsigned int atomic_o_trunc;
    unsigned int export_support;
    unsigned int writeback_cache;
    unsigned int parallel_dirops;
    unsigned int handle_killpriv;
    unsigned int cache_symlinks;
    unsigned int no_open;
    unsigned int no_opendir;
    unsigned int no_fsync;
    unsigned int no_fsyncdir;
    unsigned int no_flush;
    unsigned int no_setxattr;
    unsigned int no_getxattr;
    unsigned int no_listxattr;
    unsigned int no_removexattr;
    unsigned int no_lock;
    unsigned int no_access;
    unsigned int no_create;
    unsigned int no_interrupt;
    unsigned int no_bmap;
    unsigned int no_poll;
    unsigned int big_writes;
    unsigned int dont_mask;
    unsigned int no_flock;
    unsigned int no_fallocate;
    unsigned int no_rename2;
    unsigned int auto_inval_data;
    unsigned int explicit_inval_data;
    unsigned int do_readdirplus;
    unsigned int readdirplus_auto;
    unsigned int async_dio;
    unsigned int no_lseek;
    unsigned int posix_acl;
    unsigned int default_permissions;
    unsigned int allow_other;
    unsigned int no_copy_file_range;
    unsigned int destroy;
    unsigned int delete_stale;
    unsigned int no_control;
    unsigned int no_force_umount;
    unsigned int no_mount_options;
    atomic_t num_waiting;
    unsigned int minor;
    struct list_head entry;
    dev_t dev;
    struct dentry *[5] ctl_dentry;
    int ctl_ndents;
    u32[4] scramble_key;
    atomic64_t attr_version;
    void (*)(struct fuse_conn *) release;
    struct super_block * sb;
    struct rw_semaphore killsb;
    struct list_head devices;
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
<code>unsigned int parallel_dirops</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int no_lseek</code>
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
<code>unsigned int handle_killpriv</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int posix_acl</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int default_permissions</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int allow_other</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int bdi_initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>struct backing_dev_info bdi</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t count</code> ➡️ <code>refcount_t count</code>
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
<code>bool aborted</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int abort_err</code>
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
<code>unsigned int max_pages</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t bg_lock</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cache_symlinks</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int no_copy_file_range</code>
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
<code>unsigned int no_opendir</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int explicit_inval_data</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 khctr</code> ➡️ <code>atomic64_t khctr</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 attr_version</code> ➡️ <code>atomic64_t attr_version</code>
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
<code>unsigned int destroy</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int delete_stale</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int no_control</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int no_force_umount</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int no_mount_options</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t reserved_req_waitq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fuse_req * destroy_req</code>
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
<b>Field added. </b>
<code>unsigned int legacy_opts_show</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int handle_killpriv_v2</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int auto_submounts</code>
</li>
<li>
<b>Field added. </b>
<code>struct fuse_conn_dax * dax</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head mounts</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int no_mount_options</code>
</li>
<li>
<b>Field removed. </b>
<code>struct super_block * sb</code>
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
<code>unsigned int max_pages_limit</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int setxattr_ext</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sync_fs</code>
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
<code>struct fuse_sync_bucket * curr_bucket</code>
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
<code>unsigned int init_security</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int inode_dax</code>
</li>
<li>
<b>Field added. </b>
<code>enum fuse_dax_mode dax_mode</code>
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
<code>unsigned int no_tmpfile</code>
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
<code>unsigned int create_supp_group</code>
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
<code>unsigned int direct_io_allow_mmap</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int no_statx</code>
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

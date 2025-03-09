# Struct: <code>regmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    u8 read_flag_mask;
    u8 write_flag_mask;
    int reg_shift;
    int reg_stride;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    u8 read_flag_mask;
    u8 write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    raw_spinlock_t raw_spinlock;
    long unsigned int raw_spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    raw_spinlock_t raw_spinlock;
    long unsigned int raw_spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    unsigned int reg_base;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    int (*)(void *, const void *, size_t, void *, size_t) read;
    int (*)(void *, const void *, size_t) write;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    raw_spinlock_t raw_spinlock;
    long unsigned int raw_spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    unsigned int reg_base;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    int (*)(void *, const void *, size_t, void *, size_t) read;
    int (*)(void *, const void *, size_t) write;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    raw_spinlock_t raw_spinlock;
    long unsigned int raw_spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    unsigned int reg_base;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    int (*)(void *, const void *, size_t, void *, size_t) read;
    int (*)(void *, const void *, size_t) write;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    bool force_write_field;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    raw_spinlock_t raw_spinlock;
    long unsigned int raw_spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    unsigned int reg_base;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    int (*)(void *, const void *, size_t, void *, size_t) read;
    int (*)(void *, const void *, size_t) write;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    bool force_write_field;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
    bool can_sleep;
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
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
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
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regmap {
    struct mutex mutex;
    spinlock_t spinlock;
    long unsigned int spinlock_flags;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    gfp_t alloc_flags;
    struct device * dev;
    void * work_buf;
    struct regmap_format format;
    const struct regmap_bus * bus;
    void * bus_context;
    const char * name;
    bool async;
    spinlock_t async_lock;
    wait_queue_head_t async_waitq;
    struct list_head async_list;
    struct list_head async_free;
    int async_ret;
    bool debugfs_disable;
    struct dentry * debugfs;
    const char * debugfs_name;
    unsigned int debugfs_reg_len;
    unsigned int debugfs_val_len;
    unsigned int debugfs_tot_len;
    struct list_head debugfs_off_cache;
    struct mutex cache_lock;
    unsigned int max_register;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    bool defer_caching;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    int reg_shift;
    int reg_stride;
    int reg_stride_order;
    const struct regcache_ops * cache_ops;
    enum regcache_type cache_type;
    unsigned int cache_size_raw;
    unsigned int cache_word_size;
    unsigned int num_reg_defaults;
    unsigned int num_reg_defaults_raw;
    bool cache_only;
    bool cache_bypass;
    bool cache_free;
    struct reg_default * reg_defaults;
    const void * reg_defaults_raw;
    void * cache;
    bool cache_dirty;
    bool no_sync_defaults;
    struct reg_sequence * patch;
    int patch_regs;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    size_t max_raw_read;
    size_t max_raw_write;
    struct rb_root range_tree;
    void * selector_work_buf;
    struct hwspinlock * hwlock;
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
<code>int reg_stride_order</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u8 read_flag_mask</code> ➡️ <code>long unsigned int read_flag_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 write_flag_mask</code> ➡️ <code>long unsigned int write_flag_mask</code>
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
<code>struct hwspinlock * hwlock</code>
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
<code>bool debugfs_disable</code>
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
<code>bool (*)(struct device *, unsigned int) writeable_noinc_reg</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct device *, unsigned int) readable_noinc_reg</code>
</li>
<li>
<b>Field added. </b>
<code>const struct regmap_access_table * wr_noinc_table</code>
</li>
<li>
<b>Field added. </b>
<code>const struct regmap_access_table * rd_noinc_table</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool can_sleep</code>
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
<code>raw_spinlock_t raw_spinlock</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int raw_spinlock_flags</code>
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
<code>unsigned int reg_base</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(void *, const void *, size_t, void *, size_t) read</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(void *, const void *, size_t) write</code>
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
<code>bool force_write_field</code>
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

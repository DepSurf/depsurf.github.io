# Struct: <code>regmap_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    u8 read_flag_mask;
    u8 write_flag_mask;
    bool use_single_rw;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    u8 read_flag_mask;
    u8 write_flag_mask;
    bool use_single_rw;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool use_single_rw;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool use_single_rw;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool use_single_rw;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_rw;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool use_relaxed_mmio;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool use_relaxed_mmio;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool use_relaxed_mmio;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    bool use_raw_spinlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int reg_downshift;
    unsigned int reg_base;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    int (*)(void *, const void *, size_t, void *, size_t) read;
    int (*)(void *, const void *, size_t) write;
    size_t max_raw_read;
    size_t max_raw_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool use_relaxed_mmio;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    bool use_raw_spinlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int reg_downshift;
    unsigned int reg_base;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    int (*)(void *, const void *, size_t, void *, size_t) read;
    int (*)(void *, const void *, size_t) write;
    size_t max_raw_read;
    size_t max_raw_write;
    bool fast_io;
    bool io_port;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool use_relaxed_mmio;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    bool use_raw_spinlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int reg_shift;
    unsigned int reg_base;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    int (*)(void *, const void *, size_t, void *, size_t) read;
    int (*)(void *, const void *, size_t) write;
    size_t max_raw_read;
    size_t max_raw_write;
    bool fast_io;
    bool io_port;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool use_relaxed_mmio;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    bool use_raw_spinlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
    bool can_sleep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int reg_shift;
    unsigned int reg_base;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits;
    int (*)(void *, const void *, size_t, void *, size_t) read;
    int (*)(void *, const void *, size_t) write;
    size_t max_raw_read;
    size_t max_raw_write;
    bool fast_io;
    bool io_port;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool use_relaxed_mmio;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    bool use_raw_spinlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
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
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
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
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regmap_config {
    const char * name;
    int reg_bits;
    int reg_stride;
    int pad_bits;
    int val_bits;
    bool (*)(struct device *, unsigned int) writeable_reg;
    bool (*)(struct device *, unsigned int) readable_reg;
    bool (*)(struct device *, unsigned int) volatile_reg;
    bool (*)(struct device *, unsigned int) precious_reg;
    bool (*)(struct device *, unsigned int) writeable_noinc_reg;
    bool (*)(struct device *, unsigned int) readable_noinc_reg;
    bool disable_locking;
    regmap_lock lock;
    regmap_unlock unlock;
    void * lock_arg;
    int (*)(void *, unsigned int, unsigned int *) reg_read;
    int (*)(void *, unsigned int, unsigned int) reg_write;
    bool fast_io;
    unsigned int max_register;
    const struct regmap_access_table * wr_table;
    const struct regmap_access_table * rd_table;
    const struct regmap_access_table * volatile_table;
    const struct regmap_access_table * precious_table;
    const struct regmap_access_table * wr_noinc_table;
    const struct regmap_access_table * rd_noinc_table;
    const struct reg_default * reg_defaults;
    unsigned int num_reg_defaults;
    enum regcache_type cache_type;
    const void * reg_defaults_raw;
    unsigned int num_reg_defaults_raw;
    long unsigned int read_flag_mask;
    long unsigned int write_flag_mask;
    bool zero_flag_mask;
    bool use_single_read;
    bool use_single_write;
    bool can_multi_write;
    enum regmap_endian reg_format_endian;
    enum regmap_endian val_format_endian;
    const struct regmap_range_cfg * ranges;
    unsigned int num_ranges;
    bool use_hwlock;
    unsigned int hwlock_id;
    unsigned int hwlock_mode;
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
<code>unsigned int hwlock_id</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int hwlock_mode</code>
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
<code>bool disable_locking</code>
</li>
<li>
<b>Field added. </b>
<code>bool zero_flag_mask</code>
</li>
<li>
<b>Field added. </b>
<code>bool use_hwlock</code>
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
<li>
<b>Field added. </b>
<code>bool use_single_read</code>
</li>
<li>
<b>Field added. </b>
<code>bool use_single_write</code>
</li>
<li>
<b>Field removed. </b>
<code>bool use_single_rw</code>
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
<code>bool use_relaxed_mmio</code>
</li>
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
<code>bool use_raw_spinlock</code>
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
<code>int reg_downshift</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int reg_base</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(void *, unsigned int, unsigned int, unsigned int) reg_update_bits</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(void *, const void *, size_t, void *, size_t) read</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(void *, const void *, size_t) write</code>
</li>
<li>
<b>Field added. </b>
<code>size_t max_raw_read</code>
</li>
<li>
<b>Field added. </b>
<code>size_t max_raw_write</code>
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
<code>bool io_port</code>
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
<code>int reg_shift</code>
</li>
<li>
<b>Field removed. </b>
<code>int reg_downshift</code>
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

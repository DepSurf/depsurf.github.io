# Struct: <code>regmap_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
    bool free_on_exit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
    bool free_on_exit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_noinc_write reg_noinc_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_reg_noinc_read reg_noinc_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
    bool free_on_exit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    bool free_on_exit;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_noinc_write reg_noinc_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_reg_noinc_read reg_noinc_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    bool free_on_exit;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_noinc_write reg_noinc_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_reg_noinc_read reg_noinc_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
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
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
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
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regmap_bus {
    bool fast_io;
    regmap_hw_write write;
    regmap_hw_gather_write gather_write;
    regmap_hw_async_write async_write;
    regmap_hw_reg_write reg_write;
    regmap_hw_reg_update_bits reg_update_bits;
    regmap_hw_read read;
    regmap_hw_reg_read reg_read;
    regmap_hw_free_context free_context;
    regmap_hw_async_alloc async_alloc;
    u8 read_flag_mask;
    enum regmap_endian reg_format_endian_default;
    enum regmap_endian val_format_endian_default;
    size_t max_raw_read;
    size_t max_raw_write;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<code>bool free_on_exit</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>regmap_hw_reg_noinc_write reg_noinc_write</code>
</li>
<li>
<b>Field added. </b>
<code>regmap_hw_reg_noinc_read reg_noinc_read</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
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

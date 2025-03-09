# Struct: <code>perf_event_mmap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_user_time_short;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u32 __reserved_1;
    __u64 time_cycles;
    __u64 time_mask;
    __u8[928] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_user_time_short;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u32 __reserved_1;
    __u64 time_cycles;
    __u64 time_mask;
    __u8[928] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_user_time_short;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u32 __reserved_1;
    __u64 time_cycles;
    __u64 time_mask;
    __u8[928] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_user_time_short;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u32 __reserved_1;
    __u64 time_cycles;
    __u64 time_mask;
    __u8[928] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_user_time_short;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u32 __reserved_1;
    __u64 time_cycles;
    __u64 time_mask;
    __u8[928] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_user_time_short;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u32 __reserved_1;
    __u64 time_cycles;
    __u64 time_mask;
    __u8[928] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_user_time_short;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u32 __reserved_1;
    __u64 time_cycles;
    __u64 time_mask;
    __u8[928] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
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
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
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
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct perf_event_mmap_page {
    __u32 version;
    __u32 compat_version;
    __u32 lock;
    __u32 index;
    __s64 offset;
    __u64 time_enabled;
    __u64 time_running;
    __u64 capabilities;
    __u64 cap_bit0;
    __u64 cap_bit0_is_deprecated;
    __u64 cap_user_rdpmc;
    __u64 cap_user_time;
    __u64 cap_user_time_zero;
    __u64 cap_____res;
    __u16 pmc_width;
    __u16 time_shift;
    __u32 time_mult;
    __u64 time_offset;
    __u64 time_zero;
    __u32 size;
    __u8[948] __reserved;
    __u64 data_head;
    __u64 data_tail;
    __u64 data_offset;
    __u64 data_size;
    __u64 aux_head;
    __u64 aux_tail;
    __u64 aux_offset;
    __u64 aux_size;
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u64 cap_user_time_short</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 __reserved_1</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 time_cycles</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 time_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8[948] __reserved</code> ➡️ <code>__u8[928] __reserved</code>
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

# Struct: <code>vdso_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    struct timens_offset[12] offset;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    struct timens_offset[12] offset;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
    struct arch_vdso_data arch_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    struct timens_offset[12] offset;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
    struct arch_vdso_data arch_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    struct timens_offset[12] offset;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
    struct arch_vdso_data arch_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    struct timens_offset[12] offset;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
    struct arch_vdso_data arch_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    struct timens_offset[12] offset;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
    struct arch_vdso_data arch_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    struct timens_offset[12] offset;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
    struct arch_vdso_data arch_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    struct timens_offset[12] offset;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
    struct arch_vdso_data arch_data;
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
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq_count;
    u16 tk_is_cntvct;
    u16 cs_shift;
    u32 xtime_coarse_sec;
    u32 xtime_coarse_nsec;
    u32 wtm_clock_sec;
    u32 wtm_clock_nsec;
    u32 xtime_clock_sec;
    u32 cs_mult;
    u64 cs_cycle_last;
    u64 cs_mask;
    u64 xtime_clock_snsec;
    u32 tz_minuteswest;
    u32 tz_dsttime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vdso_data {
    __u8[16] eye_catcher;
    struct (anon) version;
    __u32 platform;
    __u32 processor;
    __u64 processorCount;
    __u64 physicalMemorySize;
    __u64 tb_orig_stamp;
    __u64 tb_ticks_per_sec;
    __u64 tb_to_xs;
    __u64 stamp_xsec;
    __u64 tb_update_count;
    __u32 tz_minuteswest;
    __u32 tz_dsttime;
    __u32 dcache_size;
    __u32 dcache_line_size;
    __u32 icache_size;
    __u32 icache_line_size;
    __u32 dcache_block_size;
    __u32 icache_block_size;
    __u32 dcache_log_block_size;
    __u32 icache_log_block_size;
    __u32 stamp_sec_fraction;
    __s32 wtom_clock_nsec;
    __s64 wtom_clock_sec;
    struct timespec stamp_xtime;
    __u32 hrtimer_res;
    __u32[14] syscall_map_64;
    __u32[14] syscall_map_32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct vdso_data {
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
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct vdso_data {
    u32 seq;
    s32 clock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vdso_timestamp[12] basetime;
    s32 tz_minuteswest;
    s32 tz_dsttime;
    u32 hrtimer_res;
    u32 __unused;
}
```
</details>
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
<code>struct timens_offset[12] offset</code>
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
<code>struct arch_vdso_data arch_data</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 seq_count</code>
</li>
<li>
<b>Field added. </b>
<code>u16 tk_is_cntvct</code>
</li>
<li>
<b>Field added. </b>
<code>u16 cs_shift</code>
</li>
<li>
<b>Field added. </b>
<code>u32 xtime_coarse_sec</code>
</li>
<li>
<b>Field added. </b>
<code>u32 xtime_coarse_nsec</code>
</li>
<li>
<b>Field added. </b>
<code>u32 wtm_clock_sec</code>
</li>
<li>
<b>Field added. </b>
<code>u32 wtm_clock_nsec</code>
</li>
<li>
<b>Field added. </b>
<code>u32 xtime_clock_sec</code>
</li>
<li>
<b>Field added. </b>
<code>u32 cs_mult</code>
</li>
<li>
<b>Field added. </b>
<code>u64 cs_cycle_last</code>
</li>
<li>
<b>Field added. </b>
<code>u64 cs_mask</code>
</li>
<li>
<b>Field added. </b>
<code>u64 xtime_clock_snsec</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 seq</code>
</li>
<li>
<b>Field removed. </b>
<code>s32 clock_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cycle_last</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 mult</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 shift</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vdso_timestamp[12] basetime</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 hrtimer_res</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 __unused</code>
</li>
<li>
<b>Field type changed. </b>
<code>s32 tz_minuteswest</code> ➡️ <code>u32 tz_minuteswest</code>
</li>
<li>
<b>Field type changed. </b>
<code>s32 tz_dsttime</code> ➡️ <code>u32 tz_dsttime</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8[16] eye_catcher</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) version</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 platform</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 processor</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 processorCount</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 physicalMemorySize</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 tb_orig_stamp</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 tb_ticks_per_sec</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 tb_to_xs</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 stamp_xsec</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 tb_update_count</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 dcache_size</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 dcache_line_size</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 icache_size</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 icache_line_size</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 dcache_block_size</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 icache_block_size</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 dcache_log_block_size</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 icache_log_block_size</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 stamp_sec_fraction</code>
</li>
<li>
<b>Field added. </b>
<code>__s32 wtom_clock_nsec</code>
</li>
<li>
<b>Field added. </b>
<code>__s64 wtom_clock_sec</code>
</li>
<li>
<b>Field added. </b>
<code>struct timespec stamp_xtime</code>
</li>
<li>
<b>Field added. </b>
<code>__u32[14] syscall_map_64</code>
</li>
<li>
<b>Field added. </b>
<code>__u32[14] syscall_map_32</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 seq</code>
</li>
<li>
<b>Field removed. </b>
<code>s32 clock_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cycle_last</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 mult</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 shift</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vdso_timestamp[12] basetime</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 __unused</code>
</li>
<li>
<b>Field type changed. </b>
<code>s32 tz_minuteswest</code> ➡️ <code>__u32 tz_minuteswest</code>
</li>
<li>
<b>Field type changed. </b>
<code>s32 tz_dsttime</code> ➡️ <code>__u32 tz_dsttime</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 hrtimer_res</code> ➡️ <code>__u32 hrtimer_res</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u32 seq</code>
</li>
<li>
<b>Field removed. </b>
<code>s32 clock_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cycle_last</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 mult</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 shift</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vdso_timestamp[12] basetime</code>
</li>
<li>
<b>Field removed. </b>
<code>s32 tz_minuteswest</code>
</li>
<li>
<b>Field removed. </b>
<code>s32 tz_dsttime</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 hrtimer_res</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 __unused</code>
</li>
</ul>
</details>
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

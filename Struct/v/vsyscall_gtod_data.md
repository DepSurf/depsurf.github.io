# Struct: <code>vsyscall_gtod_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vsyscall_gtod_data {
    unsigned int seq;
    int vclock_mode;
    cycle_t cycle_last;
    cycle_t mask;
    u32 mult;
    u32 shift;
    u64 wall_time_snsec;
    gtod_long_t wall_time_sec;
    gtod_long_t monotonic_time_sec;
    u64 monotonic_time_snsec;
    gtod_long_t wall_time_coarse_sec;
    gtod_long_t wall_time_coarse_nsec;
    gtod_long_t monotonic_time_coarse_sec;
    gtod_long_t monotonic_time_coarse_nsec;
    int tz_minuteswest;
    int tz_dsttime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vsyscall_gtod_data {
    unsigned int seq;
    int vclock_mode;
    cycle_t cycle_last;
    cycle_t mask;
    u32 mult;
    u32 shift;
    u64 wall_time_snsec;
    gtod_long_t wall_time_sec;
    gtod_long_t monotonic_time_sec;
    u64 monotonic_time_snsec;
    gtod_long_t wall_time_coarse_sec;
    gtod_long_t wall_time_coarse_nsec;
    gtod_long_t monotonic_time_coarse_sec;
    gtod_long_t monotonic_time_coarse_nsec;
    int tz_minuteswest;
    int tz_dsttime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vsyscall_gtod_data {
    unsigned int seq;
    int vclock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 wall_time_snsec;
    gtod_long_t wall_time_sec;
    gtod_long_t monotonic_time_sec;
    u64 monotonic_time_snsec;
    gtod_long_t wall_time_coarse_sec;
    gtod_long_t wall_time_coarse_nsec;
    gtod_long_t monotonic_time_coarse_sec;
    gtod_long_t monotonic_time_coarse_nsec;
    int tz_minuteswest;
    int tz_dsttime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vsyscall_gtod_data {
    unsigned int seq;
    int vclock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 wall_time_snsec;
    gtod_long_t wall_time_sec;
    gtod_long_t monotonic_time_sec;
    u64 monotonic_time_snsec;
    gtod_long_t wall_time_coarse_sec;
    gtod_long_t wall_time_coarse_nsec;
    gtod_long_t monotonic_time_coarse_sec;
    gtod_long_t monotonic_time_coarse_nsec;
    int tz_minuteswest;
    int tz_dsttime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vsyscall_gtod_data {
    unsigned int seq;
    int vclock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 wall_time_snsec;
    gtod_long_t wall_time_sec;
    gtod_long_t monotonic_time_sec;
    u64 monotonic_time_snsec;
    gtod_long_t wall_time_coarse_sec;
    gtod_long_t wall_time_coarse_nsec;
    gtod_long_t monotonic_time_coarse_sec;
    gtod_long_t monotonic_time_coarse_nsec;
    int tz_minuteswest;
    int tz_dsttime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vsyscall_gtod_data {
    unsigned int seq;
    int vclock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    u64 wall_time_snsec;
    gtod_long_t wall_time_sec;
    gtod_long_t monotonic_time_sec;
    u64 monotonic_time_snsec;
    gtod_long_t wall_time_coarse_sec;
    gtod_long_t wall_time_coarse_nsec;
    gtod_long_t monotonic_time_coarse_sec;
    gtod_long_t monotonic_time_coarse_nsec;
    int tz_minuteswest;
    int tz_dsttime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vsyscall_gtod_data {
    unsigned int seq;
    int vclock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vgtod_ts[12] basetime;
    int tz_minuteswest;
    int tz_dsttime;
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<code>cycle_t cycle_last</code> ➡️ <code>u64 cycle_last</code>
</li>
<li>
<b>Field type changed. </b>
<code>cycle_t mask</code> ➡️ <code>u64 mask</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct vgtod_ts[12] basetime</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 wall_time_snsec</code>
</li>
<li>
<b>Field removed. </b>
<code>gtod_long_t wall_time_sec</code>
</li>
<li>
<b>Field removed. </b>
<code>gtod_long_t monotonic_time_sec</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 monotonic_time_snsec</code>
</li>
<li>
<b>Field removed. </b>
<code>gtod_long_t wall_time_coarse_sec</code>
</li>
<li>
<b>Field removed. </b>
<code>gtod_long_t wall_time_coarse_nsec</code>
</li>
<li>
<b>Field removed. </b>
<code>gtod_long_t monotonic_time_coarse_sec</code>
</li>
<li>
<b>Field removed. </b>
<code>gtod_long_t monotonic_time_coarse_nsec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct vsyscall_gtod_data {
    unsigned int seq;
    int vclock_mode;
    u64 cycle_last;
    u64 mask;
    u32 mult;
    u32 shift;
    struct vgtod_ts[12] basetime;
    int tz_minuteswest;
    int tz_dsttime;
}
```
</details>
</li>
</ul>

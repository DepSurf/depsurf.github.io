# Struct: <code>disk_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    long unsigned int[2] sectors;
    long unsigned int[2] ios;
    long unsigned int[2] merges;
    long unsigned int[2] ticks;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    long unsigned int[2] sectors;
    long unsigned int[2] ios;
    long unsigned int[2] merges;
    long unsigned int[2] ticks;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    long unsigned int[2] sectors;
    long unsigned int[2] ios;
    long unsigned int[2] merges;
    long unsigned int[2] ticks;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    long unsigned int[2] sectors;
    long unsigned int[2] ios;
    long unsigned int[2] merges;
    long unsigned int[2] ticks;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    long unsigned int[2] sectors;
    long unsigned int[2] ios;
    long unsigned int[2] merges;
    long unsigned int[2] ticks;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    long unsigned int[2] sectors;
    long unsigned int[2] ios;
    long unsigned int[2] merges;
    long unsigned int[2] ticks;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[4] nsecs;
    long unsigned int[4] sectors;
    long unsigned int[4] ios;
    long unsigned int[4] merges;
    long unsigned int io_ticks;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[4] nsecs;
    long unsigned int[4] sectors;
    long unsigned int[4] ios;
    long unsigned int[4] merges;
    long unsigned int io_ticks;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[4] nsecs;
    long unsigned int[4] sectors;
    long unsigned int[4] ios;
    long unsigned int[4] merges;
    long unsigned int io_ticks;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[4] nsecs;
    long unsigned int[4] sectors;
    long unsigned int[4] ios;
    long unsigned int[4] merges;
    long unsigned int io_ticks;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[4] nsecs;
    long unsigned int[4] sectors;
    long unsigned int[4] ios;
    long unsigned int[4] merges;
    long unsigned int io_ticks;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[4] nsecs;
    long unsigned int[4] sectors;
    long unsigned int[4] ios;
    long unsigned int[4] merges;
    long unsigned int io_ticks;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[4] nsecs;
    long unsigned int[4] sectors;
    long unsigned int[4] ios;
    long unsigned int[4] merges;
    long unsigned int io_ticks;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[4] nsecs;
    long unsigned int[4] sectors;
    long unsigned int[4] ios;
    long unsigned int[4] merges;
    long unsigned int io_ticks;
    local_t[2] in_flight;
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
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
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
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct disk_stats {
    u64[3] nsecs;
    long unsigned int[3] sectors;
    long unsigned int[3] ios;
    long unsigned int[3] merges;
    long unsigned int io_ticks;
    long unsigned int time_in_queue;
    local_t[2] in_flight;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64[3] nsecs</code>
</li>
<li>
<b>Field added. </b>
<code>local_t[2] in_flight</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[2] ticks</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] sectors</code> ➡️ <code>long unsigned int[3] sectors</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] ios</code> ➡️ <code>long unsigned int[3] ios</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] merges</code> ➡️ <code>long unsigned int[3] merges</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int time_in_queue</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64[3] nsecs</code> ➡️ <code>u64[4] nsecs</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[3] sectors</code> ➡️ <code>long unsigned int[4] sectors</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[3] ios</code> ➡️ <code>long unsigned int[4] ios</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[3] merges</code> ➡️ <code>long unsigned int[4] merges</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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

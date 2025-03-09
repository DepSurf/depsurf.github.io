# Struct: <code>sugov_cpu</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cached_raw_freq;
    long unsigned int iowait_boost;
    long unsigned int iowait_boost_max;
    u64 last_update;
    long unsigned int util;
    long unsigned int max;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    long unsigned int iowait_boost;
    long unsigned int iowait_boost_max;
    u64 last_update;
    long unsigned int util;
    long unsigned int max;
    unsigned int flags;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    unsigned int iowait_boost_max;
    u64 last_update;
    long unsigned int util;
    long unsigned int max;
    unsigned int flags;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    unsigned int iowait_boost_max;
    u64 last_update;
    long unsigned int util_cfs;
    long unsigned int util_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    unsigned int iowait_boost_max;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int util;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int util;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int util;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int util;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int util;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int util;
    long unsigned int bw_dl;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int util;
    long unsigned int bw_min;
    long unsigned int saved_idle_calls;
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
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cached_raw_freq;
    long unsigned int iowait_boost;
    long unsigned int iowait_boost_max;
    u64 last_update;
    long unsigned int util;
    long unsigned int max;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int saved_idle_calls</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int cached_raw_freq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Field added. </b>
<code>bool iowait_boost_pending</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int iowait_boost</code> ➡️ <code>unsigned int iowait_boost</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int iowait_boost_max</code> ➡️ <code>unsigned int iowait_boost_max</code>
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
<code>long unsigned int util_cfs</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int util_dl</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int util</code>
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
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int bw_dl</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int util_cfs</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int util_dl</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int iowait_boost_max</code>
</li>
</ul>
</details>
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
<code>long unsigned int util</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int max</code>
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
<code>long unsigned int bw_min</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int bw_dl</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct sugov_cpu {
    struct update_util_data update_util;
    struct sugov_policy * sg_policy;
    unsigned int cpu;
    bool iowait_boost_pending;
    unsigned int iowait_boost;
    u64 last_update;
    long unsigned int bw_dl;
    long unsigned int max;
    long unsigned int saved_idle_calls;
}
```
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

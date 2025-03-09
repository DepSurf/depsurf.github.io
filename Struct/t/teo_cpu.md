# Struct: <code>teo_cpu</code>

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
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int last_state;
    int interval_idx;
    unsigned int[8] intervals;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    unsigned int[8] intervals;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    u64[8] intervals;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    u64[8] intervals;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    s64 time_span_ns;
    s64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    u64[8] intervals;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    s64 time_span_ns;
    s64 sleep_length_ns;
    struct teo_bin[10] state_bins;
    unsigned int total;
    int next_recent_idx;
    int[9] recent_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    s64 time_span_ns;
    s64 sleep_length_ns;
    struct teo_bin[10] state_bins;
    unsigned int total;
    int next_recent_idx;
    int[9] recent_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    s64 time_span_ns;
    s64 sleep_length_ns;
    struct teo_bin[10] state_bins;
    unsigned int total;
    int next_recent_idx;
    int[9] recent_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    s64 time_span_ns;
    s64 sleep_length_ns;
    struct teo_bin[10] state_bins;
    unsigned int total;
    int next_recent_idx;
    int[9] recent_idx;
    long unsigned int util_threshold;
    bool utilized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    s64 time_span_ns;
    s64 sleep_length_ns;
    struct teo_bin[10] state_bins;
    unsigned int total;
    int next_recent_idx;
    int[9] recent_idx;
    unsigned int tick_hits;
    long unsigned int util_threshold;
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
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    unsigned int[8] intervals;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    unsigned int[8] intervals;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    unsigned int[8] intervals;
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
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    unsigned int[8] intervals;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    unsigned int[8] intervals;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    unsigned int[8] intervals;
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
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int last_state;
    int interval_idx;
    unsigned int[8] intervals;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int last_state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int[8] intervals</code> ➡️ <code>u64[8] intervals</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u64 time_span_ns</code> ➡️ <code>s64 time_span_ns</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 sleep_length_ns</code> ➡️ <code>s64 sleep_length_ns</code>
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
<code>struct teo_bin[10] state_bins</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int total</code>
</li>
<li>
<b>Field added. </b>
<code>int next_recent_idx</code>
</li>
<li>
<b>Field added. </b>
<code>int[9] recent_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>struct teo_idle_state[10] states</code>
</li>
<li>
<b>Field removed. </b>
<code>int interval_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[8] intervals</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>long unsigned int util_threshold</code>
</li>
<li>
<b>Field added. </b>
<code>bool utilized</code>
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
<code>unsigned int tick_hits</code>
</li>
<li>
<b>Field removed. </b>
<code>bool utilized</code>
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
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    unsigned int[8] intervals;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct teo_cpu {
    u64 time_span_ns;
    u64 sleep_length_ns;
    struct teo_idle_state[10] states;
    int interval_idx;
    unsigned int[8] intervals;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

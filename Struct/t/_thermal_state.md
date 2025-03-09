# Struct: <code>_thermal_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    u64 next_check;
    u64 last_interrupt_time;
    struct delayed_work therm_work;
    long unsigned int count;
    long unsigned int last_count;
    long unsigned int max_time_ms;
    long unsigned int total_time_ms;
    bool rate_control_active;
    bool new_event;
    u8 level;
    u8 sample_index;
    u8 sample_count;
    u8 average;
    u8 baseline_temp;
    u8[3] temp_samples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    u64 next_check;
    u64 last_interrupt_time;
    struct delayed_work therm_work;
    long unsigned int count;
    long unsigned int last_count;
    long unsigned int max_time_ms;
    long unsigned int total_time_ms;
    bool rate_control_active;
    bool new_event;
    u8 level;
    u8 sample_index;
    u8 sample_count;
    u8 average;
    u8 baseline_temp;
    u8[3] temp_samples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    u64 next_check;
    u64 last_interrupt_time;
    struct delayed_work therm_work;
    long unsigned int count;
    long unsigned int last_count;
    long unsigned int max_time_ms;
    long unsigned int total_time_ms;
    bool rate_control_active;
    bool new_event;
    u8 level;
    u8 sample_index;
    u8 sample_count;
    u8 average;
    u8 baseline_temp;
    u8[3] temp_samples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    u64 next_check;
    u64 last_interrupt_time;
    struct delayed_work therm_work;
    long unsigned int count;
    long unsigned int last_count;
    long unsigned int max_time_ms;
    long unsigned int total_time_ms;
    bool rate_control_active;
    bool new_event;
    u8 level;
    u8 sample_index;
    u8 sample_count;
    u8 average;
    u8 baseline_temp;
    u8[3] temp_samples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    u64 next_check;
    u64 last_interrupt_time;
    struct delayed_work therm_work;
    long unsigned int count;
    long unsigned int last_count;
    long unsigned int max_time_ms;
    long unsigned int total_time_ms;
    bool rate_control_active;
    bool new_event;
    u8 level;
    u8 sample_index;
    u8 sample_count;
    u8 average;
    u8 baseline_temp;
    u8[3] temp_samples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    u64 next_check;
    u64 last_interrupt_time;
    struct delayed_work therm_work;
    long unsigned int count;
    long unsigned int last_count;
    long unsigned int max_time_ms;
    long unsigned int total_time_ms;
    bool rate_control_active;
    bool new_event;
    u8 level;
    u8 sample_index;
    u8 sample_count;
    u8 average;
    u8 baseline_temp;
    u8[3] temp_samples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    u64 next_check;
    u64 last_interrupt_time;
    struct delayed_work therm_work;
    long unsigned int count;
    long unsigned int last_count;
    long unsigned int max_time_ms;
    long unsigned int total_time_ms;
    bool rate_control_active;
    bool new_event;
    u8 level;
    u8 sample_index;
    u8 sample_count;
    u8 average;
    u8 baseline_temp;
    u8[3] temp_samples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    u64 next_check;
    u64 last_interrupt_time;
    struct delayed_work therm_work;
    long unsigned int count;
    long unsigned int last_count;
    long unsigned int max_time_ms;
    long unsigned int total_time_ms;
    bool rate_control_active;
    bool new_event;
    u8 level;
    u8 sample_index;
    u8 sample_count;
    u8 average;
    u8 baseline_temp;
    u8[3] temp_samples;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 last_interrupt_time</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work therm_work</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int max_time_ms</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int total_time_ms</code>
</li>
<li>
<b>Field added. </b>
<code>bool rate_control_active</code>
</li>
<li>
<b>Field added. </b>
<code>u8 level</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sample_index</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sample_count</code>
</li>
<li>
<b>Field added. </b>
<code>u8 average</code>
</li>
<li>
<b>Field added. </b>
<code>u8 baseline_temp</code>
</li>
<li>
<b>Field added. </b>
<code>u8[3] temp_samples</code>
</li>
<li>
<b>Field removed. </b>
<code>int event</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct _thermal_state {
    bool new_event;
    int event;
    u64 next_check;
    long unsigned int count;
    long unsigned int last_count;
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

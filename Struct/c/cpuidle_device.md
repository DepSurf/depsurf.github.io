# Struct: <code>cpuidle_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int cpu;
    int last_residency;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int cpu;
    int last_residency;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int cpu;
    int last_residency;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int cpu;
    int last_residency;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int cpu;
    int last_residency;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int cpu;
    int last_residency;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    int last_residency;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_residency;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    int last_residency;
    u64 poll_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    u64 last_residency_ns;
    u64 poll_limit_ns;
    u64 forced_idle_latency_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    u64 last_residency_ns;
    u64 poll_limit_ns;
    u64 forced_idle_latency_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    u64 last_residency_ns;
    u64 poll_limit_ns;
    u64 forced_idle_latency_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    u64 last_residency_ns;
    u64 poll_limit_ns;
    u64 forced_idle_latency_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    u64 last_residency_ns;
    u64 poll_limit_ns;
    u64 forced_idle_latency_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    u64 last_residency_ns;
    u64 poll_limit_ns;
    u64 forced_idle_latency_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    u64 last_residency_ns;
    u64 poll_limit_ns;
    u64 forced_idle_latency_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    u64 last_residency_ns;
    u64 poll_limit_ns;
    u64 forced_idle_latency_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
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
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    int last_residency;
    u64 poll_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    int last_residency;
    u64 poll_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
    cpumask_t coupled_cpus;
    struct cpuidle_coupled * coupled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    int last_residency;
    u64 poll_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    int last_residency;
    u64 poll_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
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
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    int last_residency;
    u64 poll_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    int last_residency;
    u64 poll_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    int last_residency;
    u64 poll_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cpuidle_device {
    unsigned int registered;
    unsigned int enabled;
    unsigned int use_deepest_state;
    unsigned int poll_time_limit;
    unsigned int cpu;
    ktime_t next_hrtimer;
    int last_state_idx;
    int last_residency;
    u64 poll_limit_ns;
    struct cpuidle_state_usage[10] states_usage;
    struct cpuidle_state_kobj *[10] kobjs;
    struct cpuidle_driver_kobj * kobj_driver;
    struct cpuidle_device_kobj * kobj_dev;
    struct list_head device_list;
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
<b>Field added. </b>
<code>unsigned int use_deepest_state</code>
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
<code>unsigned int poll_time_limit</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>ktime_t next_hrtimer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int last_state_idx</code>
</li>
<li>
<b>Field added. </b>
<code>u64 poll_limit_ns</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 last_residency_ns</code>
</li>
<li>
<b>Field added. </b>
<code>u64 forced_idle_latency_limit_ns</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int use_deepest_state</code>
</li>
<li>
<b>Field removed. </b>
<code>int last_residency</code>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct cpuidle_driver_kobj * kobj_driver</code> ➡️ <code>struct cpuidle_driver_kobj * kobj_driver</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>cpumask_t coupled_cpus</code>
</li>
<li>
<b>Field added. </b>
<code>struct cpuidle_coupled * coupled</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct cpuidle_driver_kobj * kobj_driver</code> ➡️ <code>struct cpuidle_driver_kobj * kobj_driver</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct cpuidle_state_kobj *[10] kobjs</code> ➡️ <code>struct cpuidle_state_kobj *[10] kobjs</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct cpuidle_device_kobj * kobj_dev</code> ➡️ <code>struct cpuidle_device_kobj * kobj_dev</code>
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

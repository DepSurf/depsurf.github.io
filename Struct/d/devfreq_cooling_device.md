# Struct: <code>devfreq_cooling_device</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
    struct dev_pm_qos_request req_max_freq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * freq_table;
    size_t max_state;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
    struct dev_pm_qos_request req_max_freq;
    struct em_perf_domain * em_pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * freq_table;
    size_t max_state;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
    struct dev_pm_qos_request req_max_freq;
    struct em_perf_domain * em_pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * freq_table;
    size_t max_state;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
    struct dev_pm_qos_request req_max_freq;
    struct em_perf_domain * em_pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * freq_table;
    size_t max_state;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
    struct dev_pm_qos_request req_max_freq;
    struct em_perf_domain * em_pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    struct thermal_cooling_device * cdev;
    struct thermal_cooling_device_ops cooling_ops;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * freq_table;
    size_t max_state;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
    struct dev_pm_qos_request req_max_freq;
    struct em_perf_domain * em_pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    struct thermal_cooling_device * cdev;
    struct thermal_cooling_device_ops cooling_ops;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * freq_table;
    size_t max_state;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
    struct dev_pm_qos_request req_max_freq;
    struct em_perf_domain * em_pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    struct thermal_cooling_device * cdev;
    struct thermal_cooling_device_ops cooling_ops;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * freq_table;
    size_t max_state;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
    struct dev_pm_qos_request req_max_freq;
    struct em_perf_domain * em_pd;
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
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
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
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct devfreq_cooling_device {
    int id;
    struct thermal_cooling_device * cdev;
    struct devfreq * devfreq;
    long unsigned int cooling_state;
    u32 * power_table;
    u32 * freq_table;
    size_t freq_table_size;
    struct devfreq_cooling_power * power_ops;
    u32 res_util;
    int capped_state;
}
```
</details>
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
<code>struct dev_pm_qos_request req_max_freq</code>
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
<code>size_t max_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct em_perf_domain * em_pd</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 * power_table</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t freq_table_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<code>struct thermal_cooling_device_ops cooling_ops</code>
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

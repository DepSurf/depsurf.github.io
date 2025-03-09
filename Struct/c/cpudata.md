# Struct: <code>cpudata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    struct timer_list timer;
    struct pstate_data pstate;
    struct vid_data vid;
    struct _pid pid;
    ktime_t last_sample_time;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    struct sample sample;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    struct _pid pid;
    u64 last_sample_time;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    struct _pid pid;
    u64 last_update;
    u64 last_sample_time;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    struct perf_limits * perf_limits;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    struct _pid pid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_cached;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
    bool suspended;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_cached;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
    bool suspended;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_cached;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
    bool suspended;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_cached;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
    bool suspended;
    struct delayed_work hwp_notify_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_cached;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
    bool suspended;
    struct delayed_work hwp_notify_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_cached;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
    bool suspended;
    struct delayed_work hwp_notify_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_cached;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
    bool suspended;
    struct delayed_work hwp_notify_work;
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
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct update_util_data update_util</code>
</li>
<li>
<b>Field added. </b>
<code>bool update_util_set</code>
</li>
<li>
<b>Field added. </b>
<code>u64 prev_cummulative_iowait</code>
</li>
<li>
<b>Field added. </b>
<code>struct acpi_processor_performance acpi_perf_data</code>
</li>
<li>
<b>Field added. </b>
<code>bool valid_pss_table</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list timer</code>
</li>
<li>
<b>Field type changed. </b>
<code>ktime_t last_sample_time</code> ➡️ <code>u64 last_sample_time</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int policy</code>
</li>
<li>
<b>Field added. </b>
<code>u64 last_update</code>
</li>
<li>
<b>Field added. </b>
<code>struct perf_limits * perf_limits</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int iowait_boost</code>
</li>
<li>
<b>Field added. </b>
<code>s16 epp_powersave</code>
</li>
<li>
<b>Field added. </b>
<code>s16 epp_policy</code>
</li>
<li>
<b>Field added. </b>
<code>s16 epp_default</code>
</li>
<li>
<b>Field added. </b>
<code>s16 epp_saved</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 aperf_mperf_shift</code>
</li>
<li>
<b>Field added. </b>
<code>int32_t min_perf_ratio</code>
</li>
<li>
<b>Field added. </b>
<code>int32_t max_perf_ratio</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_limits * perf_limits</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct _pid pid</code>
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
<code>u64 hwp_req_cached</code>
</li>
<li>
<b>Field added. </b>
<code>u64 hwp_cap_cached</code>
</li>
<li>
<b>Field added. </b>
<code>u64 last_io_update</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sched_flags</code>
</li>
<li>
<b>Field added. </b>
<code>u32 hwp_boost_min</code>
</li>
</ul>
</details>
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
<code>s16 epp_cached</code>
</li>
<li>
<b>Field added. </b>
<code>bool suspended</code>
</li>
<li>
<b>Field removed. </b>
<code>s16 epp_saved</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct delayed_work hwp_notify_work</code>
</li>
</ul>
</details>
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
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpudata {
    int cpu;
    unsigned int policy;
    struct update_util_data update_util;
    bool update_util_set;
    struct pstate_data pstate;
    struct vid_data vid;
    u64 last_update;
    u64 last_sample_time;
    u64 aperf_mperf_shift;
    u64 prev_aperf;
    u64 prev_mperf;
    u64 prev_tsc;
    u64 prev_cummulative_iowait;
    struct sample sample;
    int32_t min_perf_ratio;
    int32_t max_perf_ratio;
    struct acpi_processor_performance acpi_perf_data;
    bool valid_pss_table;
    unsigned int iowait_boost;
    s16 epp_powersave;
    s16 epp_policy;
    s16 epp_default;
    s16 epp_saved;
    u64 hwp_req_cached;
    u64 hwp_cap_cached;
    u64 last_io_update;
    unsigned int sched_flags;
    u32 hwp_boost_min;
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

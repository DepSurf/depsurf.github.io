# Struct: <code>perf_dom_info</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct perf_dom_info {
    bool set_limits;
    bool set_perf;
    bool perf_limit_notify;
    bool perf_level_notify;
    bool perf_fastchannels;
    u32 opp_count;
    u32 sustained_freq_khz;
    u32 sustained_perf_level;
    u32 mult_factor;
    char[16] name;
    struct scmi_opp[16] opp;
    struct scmi_fc_info * fc_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct perf_dom_info {
    bool set_limits;
    bool set_perf;
    bool perf_limit_notify;
    bool perf_level_notify;
    bool perf_fastchannels;
    u32 opp_count;
    u32 sustained_freq_khz;
    u32 sustained_perf_level;
    u32 mult_factor;
    char[16] name;
    struct scmi_opp[16] opp;
    struct scmi_fc_info * fc_info;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct perf_dom_info {
    bool set_limits;
    bool set_perf;
    bool perf_limit_notify;
    bool perf_level_notify;
    bool perf_fastchannels;
    u32 opp_count;
    u32 sustained_freq_khz;
    u32 sustained_perf_level;
    u32 mult_factor;
    char[16] name;
    struct scmi_opp[16] opp;
    struct scmi_fc_info * fc_info;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct perf_dom_info {
    bool set_limits;
    bool set_perf;
    bool perf_limit_notify;
    bool perf_level_notify;
    bool perf_fastchannels;
    u32 opp_count;
    u32 sustained_freq_khz;
    u32 sustained_perf_level;
    u32 mult_factor;
    char[16] name;
    struct scmi_opp[16] opp;
    struct scmi_fc_info * fc_info;
}
```
</details>
</li>
</ul>

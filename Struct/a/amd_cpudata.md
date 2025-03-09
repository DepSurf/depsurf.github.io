# Struct: <code>amd_cpudata</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct amd_cpudata {
    int cpu;
    struct freq_qos_request[2] req;
    u64 cppc_req_cached;
    u32 highest_perf;
    u32 nominal_perf;
    u32 lowest_nonlinear_perf;
    u32 lowest_perf;
    u32 max_freq;
    u32 min_freq;
    u32 nominal_freq;
    u32 lowest_nonlinear_freq;
    struct amd_aperf_mperf cur;
    struct amd_aperf_mperf prev;
    u64 freq;
    bool boost_supported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct amd_cpudata {
    int cpu;
    struct freq_qos_request[2] req;
    u64 cppc_req_cached;
    u32 highest_perf;
    u32 nominal_perf;
    u32 lowest_nonlinear_perf;
    u32 lowest_perf;
    u32 max_freq;
    u32 min_freq;
    u32 nominal_freq;
    u32 lowest_nonlinear_freq;
    struct amd_aperf_mperf cur;
    struct amd_aperf_mperf prev;
    u64 freq;
    bool boost_supported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct amd_cpudata {
    int cpu;
    struct freq_qos_request[2] req;
    u64 cppc_req_cached;
    u32 highest_perf;
    u32 nominal_perf;
    u32 lowest_nonlinear_perf;
    u32 lowest_perf;
    u32 max_freq;
    u32 min_freq;
    u32 nominal_freq;
    u32 lowest_nonlinear_freq;
    struct amd_aperf_mperf cur;
    struct amd_aperf_mperf prev;
    u64 freq;
    bool boost_supported;
    s16 epp_policy;
    s16 epp_cached;
    u32 policy;
    u64 cppc_cap1_cached;
    bool suspended;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct amd_cpudata {
    int cpu;
    struct freq_qos_request[2] req;
    u64 cppc_req_cached;
    u32 highest_perf;
    u32 nominal_perf;
    u32 lowest_nonlinear_perf;
    u32 lowest_perf;
    u32 min_limit_perf;
    u32 max_limit_perf;
    u32 min_limit_freq;
    u32 max_limit_freq;
    u32 max_freq;
    u32 min_freq;
    u32 nominal_freq;
    u32 lowest_nonlinear_freq;
    struct amd_aperf_mperf cur;
    struct amd_aperf_mperf prev;
    u64 freq;
    bool boost_supported;
    s16 epp_policy;
    s16 epp_cached;
    u32 policy;
    u64 cppc_cap1_cached;
    bool suspended;
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
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct amd_cpudata {
    int cpu;
    struct freq_qos_request[2] req;
    u64 cppc_req_cached;
    u32 highest_perf;
    u32 nominal_perf;
    u32 lowest_nonlinear_perf;
    u32 lowest_perf;
    u32 max_freq;
    u32 min_freq;
    u32 nominal_freq;
    u32 lowest_nonlinear_freq;
    struct amd_aperf_mperf cur;
    struct amd_aperf_mperf prev;
    u64 freq;
    bool boost_supported;
}
```
</details>
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
<code>s16 epp_policy</code>
</li>
<li>
<b>Field added. </b>
<code>s16 epp_cached</code>
</li>
<li>
<b>Field added. </b>
<code>u32 policy</code>
</li>
<li>
<b>Field added. </b>
<code>u64 cppc_cap1_cached</code>
</li>
<li>
<b>Field added. </b>
<code>bool suspended</code>
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
<code>u32 min_limit_perf</code>
</li>
<li>
<b>Field added. </b>
<code>u32 max_limit_perf</code>
</li>
<li>
<b>Field added. </b>
<code>u32 min_limit_freq</code>
</li>
<li>
<b>Field added. </b>
<code>u32 max_limit_freq</code>
</li>
</ul>
</details>
</li>
</ul>

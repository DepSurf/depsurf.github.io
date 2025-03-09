# Struct: <code>cci_pmu_model</code>

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
struct cci_pmu_model {
    char * name;
    u32 fixed_hw_cntrs;
    u32 num_hw_cntrs;
    u32 cntr_size;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    struct event_range[3] event_ranges;
    int (*)(struct cci_pmu *, long unsigned int) validate_hw_event;
    int (*)(struct cci_pmu *, struct cci_pmu_hw_events *, long unsigned int) get_event_idx;
    void (*)(struct cci_pmu *, long unsigned int *) write_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cci_pmu_model {
    char * name;
    u32 fixed_hw_cntrs;
    u32 num_hw_cntrs;
    u32 cntr_size;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    struct event_range[3] event_ranges;
    int (*)(struct cci_pmu *, long unsigned int) validate_hw_event;
    int (*)(struct cci_pmu *, struct cci_pmu_hw_events *, long unsigned int) get_event_idx;
    void (*)(struct cci_pmu *, long unsigned int *) write_counters;
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
struct cci_pmu_model {
    char * name;
    u32 fixed_hw_cntrs;
    u32 num_hw_cntrs;
    u32 cntr_size;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    struct event_range[3] event_ranges;
    int (*)(struct cci_pmu *, long unsigned int) validate_hw_event;
    int (*)(struct cci_pmu *, struct cci_pmu_hw_events *, long unsigned int) get_event_idx;
    void (*)(struct cci_pmu *, long unsigned int *) write_counters;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct cci_pmu_model {
    char * name;
    u32 fixed_hw_cntrs;
    u32 num_hw_cntrs;
    u32 cntr_size;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    struct event_range[3] event_ranges;
    int (*)(struct cci_pmu *, long unsigned int) validate_hw_event;
    int (*)(struct cci_pmu *, struct cci_pmu_hw_events *, long unsigned int) get_event_idx;
    void (*)(struct cci_pmu *, long unsigned int *) write_counters;
}
```
</details>
</li>
</ul>

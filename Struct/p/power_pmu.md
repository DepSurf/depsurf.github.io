# Struct: <code>power_pmu</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct power_pmu {
    const char * name;
    int n_counter;
    int max_alternatives;
    long unsigned int add_fields;
    long unsigned int test_adder;
    int (*)(u64 *, int, unsigned int *, long unsigned int *, struct perf_event * *) compute_mmcr;
    int (*)(u64, long unsigned int *, long unsigned int *) get_constraint;
    int (*)(u64, unsigned int, u64 *) get_alternatives;
    void (*)(union perf_mem_data_src *, u32, struct pt_regs *) get_mem_data_src;
    void (*)(u64 *) get_mem_weight;
    long unsigned int group_constraint_mask;
    long unsigned int group_constraint_val;
    u64 (*)(u64) bhrb_filter_map;
    void (*)(u64) config_bhrb;
    void (*)(unsigned int, long unsigned int *) disable_pmc;
    int (*)(u64) limited_pmc_event;
    u32 flags;
    const struct attribute_group * * attr_groups;
    int n_generic;
    int * generic_events;
    int[42] * cache_events;
    int n_blacklist_ev;
    int * blacklist_ev;
    int bhrb_nr;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct power_pmu {
    const char * name;
    int n_counter;
    int max_alternatives;
    long unsigned int add_fields;
    long unsigned int test_adder;
    int (*)(u64 *, int, unsigned int *, long unsigned int *, struct perf_event * *) compute_mmcr;
    int (*)(u64, long unsigned int *, long unsigned int *) get_constraint;
    int (*)(u64, unsigned int, u64 *) get_alternatives;
    void (*)(union perf_mem_data_src *, u32, struct pt_regs *) get_mem_data_src;
    void (*)(u64 *) get_mem_weight;
    long unsigned int group_constraint_mask;
    long unsigned int group_constraint_val;
    u64 (*)(u64) bhrb_filter_map;
    void (*)(u64) config_bhrb;
    void (*)(unsigned int, long unsigned int *) disable_pmc;
    int (*)(u64) limited_pmc_event;
    u32 flags;
    const struct attribute_group * * attr_groups;
    int n_generic;
    int * generic_events;
    int[42] * cache_events;
    int n_blacklist_ev;
    int * blacklist_ev;
    int bhrb_nr;
}
```
</details>
</li>
</ul>

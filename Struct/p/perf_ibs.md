# Struct: <code>perf_ibs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    unsigned int fetch_count_reset_broken;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    unsigned int fetch_count_reset_broken;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    unsigned int fetch_count_reset_broken;
    unsigned int fetch_ignore_if_zero_rip;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    unsigned int fetch_count_reset_broken;
    unsigned int fetch_ignore_if_zero_rip;
    struct cpu_perf_ibs * pcpu;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    unsigned int fetch_count_reset_broken;
    unsigned int fetch_ignore_if_zero_rip;
    struct cpu_perf_ibs * pcpu;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    unsigned int fetch_count_reset_broken;
    unsigned int fetch_ignore_if_zero_rip;
    struct cpu_perf_ibs * pcpu;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    unsigned int fetch_count_reset_broken;
    unsigned int fetch_ignore_if_zero_rip;
    struct cpu_perf_ibs * pcpu;
    u64 (*)(u64) get_count;
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
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int fetch_count_reset_broken</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int fetch_ignore_if_zero_rip</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct attribute * * format_attrs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct attribute_group format_group</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct attribute_group *[2] attr_groups</code>
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
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct perf_ibs {
    struct pmu pmu;
    unsigned int msr;
    u64 config_mask;
    u64 cnt_mask;
    u64 enable_mask;
    u64 valid_mask;
    u64 max_period;
    long unsigned int[1] offset_mask;
    int offset_max;
    struct cpu_perf_ibs * pcpu;
    struct attribute * * format_attrs;
    struct attribute_group format_group;
    const struct attribute_group *[2] attr_groups;
    u64 (*)(u64) get_count;
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

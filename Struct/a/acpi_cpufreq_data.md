# Struct: <code>acpi_cpufreq_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    struct cpufreq_frequency_table * freq_table;
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
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
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
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
<code>void (*)(struct acpi_pct_register *, u32) cpu_freq_write</code>
</li>
<li>
<b>Field added. </b>
<code>u32 (*)(struct acpi_pct_register *) cpu_freq_read</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cpufreq_frequency_table * freq_table</code>
</li>
</ul>
</details>
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
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_cpufreq_data {
    unsigned int resume;
    unsigned int cpu_feature;
    unsigned int acpi_perf_cpu;
    cpumask_var_t freqdomain_cpus;
    void (*)(struct acpi_pct_register *, u32) cpu_freq_write;
    u32 (*)(struct acpi_pct_register *) cpu_freq_read;
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

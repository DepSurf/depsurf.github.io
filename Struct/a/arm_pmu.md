# Struct: <code>arm_pmu</code>

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
struct arm_pmu {
    struct pmu pmu;
    cpumask_t supported_cpus;
    char * name;
    irqreturn_t (*)(struct arm_pmu *) handle_irq;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    int (*)(struct pmu_hw_events *, struct perf_event *) get_event_idx;
    void (*)(struct pmu_hw_events *, struct perf_event *) clear_event_idx;
    int (*)(struct hw_perf_event *, struct perf_event_attr *) set_event_filter;
    u64 (*)(struct perf_event *) read_counter;
    void (*)(struct perf_event *, u64) write_counter;
    void (*)(struct arm_pmu *) start;
    void (*)(struct arm_pmu *) stop;
    void (*)(void *) reset;
    int (*)(struct perf_event *) map_event;
    int (*)(struct perf_event *) filter_match;
    int num_events;
    bool secure_access;
    long unsigned int[1] pmceid_bitmap;
    long unsigned int[1] pmceid_ext_bitmap;
    struct platform_device * plat_device;
    struct pmu_hw_events * hw_events;
    struct hlist_node node;
    struct notifier_block cpu_pm_nb;
    const struct attribute_group *[4] attr_groups;
    long unsigned int acpi_cpuid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct arm_pmu {
    struct pmu pmu;
    cpumask_t supported_cpus;
    char * name;
    irqreturn_t (*)(struct arm_pmu *) handle_irq;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    int (*)(struct pmu_hw_events *, struct perf_event *) get_event_idx;
    void (*)(struct pmu_hw_events *, struct perf_event *) clear_event_idx;
    int (*)(struct hw_perf_event *, struct perf_event_attr *) set_event_filter;
    u64 (*)(struct perf_event *) read_counter;
    void (*)(struct perf_event *, u64) write_counter;
    void (*)(struct arm_pmu *) start;
    void (*)(struct arm_pmu *) stop;
    void (*)(void *) reset;
    int (*)(struct perf_event *) map_event;
    int (*)(struct perf_event *) filter_match;
    int num_events;
    bool secure_access;
    long unsigned int[2] pmceid_bitmap;
    long unsigned int[2] pmceid_ext_bitmap;
    struct platform_device * plat_device;
    struct pmu_hw_events * hw_events;
    struct hlist_node node;
    struct notifier_block cpu_pm_nb;
    const struct attribute_group *[4] attr_groups;
    long unsigned int acpi_cpuid;
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
struct arm_pmu {
    struct pmu pmu;
    cpumask_t supported_cpus;
    char * name;
    irqreturn_t (*)(struct arm_pmu *) handle_irq;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    int (*)(struct pmu_hw_events *, struct perf_event *) get_event_idx;
    void (*)(struct pmu_hw_events *, struct perf_event *) clear_event_idx;
    int (*)(struct hw_perf_event *, struct perf_event_attr *) set_event_filter;
    u64 (*)(struct perf_event *) read_counter;
    void (*)(struct perf_event *, u64) write_counter;
    void (*)(struct arm_pmu *) start;
    void (*)(struct arm_pmu *) stop;
    void (*)(void *) reset;
    int (*)(struct perf_event *) map_event;
    int (*)(struct perf_event *) filter_match;
    int num_events;
    bool secure_access;
    long unsigned int[1] pmceid_bitmap;
    long unsigned int[1] pmceid_ext_bitmap;
    struct platform_device * plat_device;
    struct pmu_hw_events * hw_events;
    struct hlist_node node;
    struct notifier_block cpu_pm_nb;
    const struct attribute_group *[4] attr_groups;
    long unsigned int acpi_cpuid;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct arm_pmu {
    struct pmu pmu;
    cpumask_t supported_cpus;
    char * name;
    irqreturn_t (*)(struct arm_pmu *) handle_irq;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    int (*)(struct pmu_hw_events *, struct perf_event *) get_event_idx;
    void (*)(struct pmu_hw_events *, struct perf_event *) clear_event_idx;
    int (*)(struct hw_perf_event *, struct perf_event_attr *) set_event_filter;
    u64 (*)(struct perf_event *) read_counter;
    void (*)(struct perf_event *, u64) write_counter;
    void (*)(struct arm_pmu *) start;
    void (*)(struct arm_pmu *) stop;
    void (*)(void *) reset;
    int (*)(struct perf_event *) map_event;
    int (*)(struct perf_event *) filter_match;
    int num_events;
    bool secure_access;
    long unsigned int[2] pmceid_bitmap;
    long unsigned int[2] pmceid_ext_bitmap;
    struct platform_device * plat_device;
    struct pmu_hw_events * hw_events;
    struct hlist_node node;
    struct notifier_block cpu_pm_nb;
    const struct attribute_group *[4] attr_groups;
    long unsigned int acpi_cpuid;
}
```
</details>
</li>
</ul>

# Struct: <code>iommu_pmu</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iommu_pmu {
    struct intel_iommu * iommu;
    u32 num_cntr;
    u32 num_eg;
    u32 cntr_width;
    u32 cntr_stride;
    u32 filter;
    void * base;
    void * cfg_reg;
    void * cntr_reg;
    void * overflow;
    u64 * evcap;
    u32 * * cntr_evcap;
    struct pmu pmu;
    long unsigned int[1] used_mask;
    struct perf_event *[64] event_list;
    unsigned char[16] irq_name;
    struct hlist_node cpuhp_node;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iommu_pmu {
    struct intel_iommu * iommu;
    u32 num_cntr;
    u32 num_eg;
    u32 cntr_width;
    u32 cntr_stride;
    u32 filter;
    void * base;
    void * cfg_reg;
    void * cntr_reg;
    void * overflow;
    u64 * evcap;
    u32 * * cntr_evcap;
    struct pmu pmu;
    long unsigned int[1] used_mask;
    struct perf_event *[64] event_list;
    unsigned char[16] irq_name;
    struct hlist_node cpuhp_node;
    int cpu;
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct iommu_pmu {
    struct intel_iommu * iommu;
    u32 num_cntr;
    u32 num_eg;
    u32 cntr_width;
    u32 cntr_stride;
    u32 filter;
    void * base;
    void * cfg_reg;
    void * cntr_reg;
    void * overflow;
    u64 * evcap;
    u32 * * cntr_evcap;
    struct pmu pmu;
    long unsigned int[1] used_mask;
    struct perf_event *[64] event_list;
    unsigned char[16] irq_name;
    struct hlist_node cpuhp_node;
    int cpu;
}
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

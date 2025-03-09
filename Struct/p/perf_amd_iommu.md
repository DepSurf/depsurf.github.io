# Struct: <code>perf_amd_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct pmu pmu;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
    const struct attribute_group *[4] attr_groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct pmu pmu;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
    const struct attribute_group *[4] attr_groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct pmu pmu;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
    const struct attribute_group *[4] attr_groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
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
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field added. </b>
<code>struct amd_iommu * iommu</code>
</li>
<li>
<b>Field added. </b>
<code>char[16] name</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct attribute_group *[4] attr_groups</code>
</li>
</ul>
</details>
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
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct perf_amd_iommu {
    struct list_head list;
    struct pmu pmu;
    struct amd_iommu * iommu;
    char[16] name;
    u8 max_banks;
    u8 max_counters;
    u64 cntr_assign_mask;
    raw_spinlock_t lock;
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

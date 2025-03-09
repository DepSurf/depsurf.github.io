# Struct: <code>arm_smmu_device</code>

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
struct arm_smmu_device {
    struct device * dev;
    void * base;
    unsigned int numpage;
    unsigned int pgshift;
    u32 features;
    enum arm_smmu_arch_version version;
    enum arm_smmu_implementation model;
    const struct arm_smmu_impl * impl;
    u32 num_context_banks;
    u32 num_s2_context_banks;
    long unsigned int[2] context_map;
    struct arm_smmu_cb * cbs;
    atomic_t irptndx;
    u32 num_mapping_groups;
    u16 streamid_mask;
    u16 smr_mask_mask;
    struct arm_smmu_smr * smrs;
    struct arm_smmu_s2cr * s2crs;
    struct mutex stream_map_mutex;
    long unsigned int va_size;
    long unsigned int ipa_size;
    long unsigned int pa_size;
    long unsigned int pgsize_bitmap;
    u32 num_global_irqs;
    u32 num_context_irqs;
    unsigned int * irqs;
    struct clk_bulk_data * clks;
    int num_clks;
    spinlock_t global_sync_lock;
    struct iommu_device iommu;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct arm_smmu_device {
    struct device * dev;
    void * base;
    unsigned int numpage;
    unsigned int pgshift;
    u32 features;
    enum arm_smmu_arch_version version;
    enum arm_smmu_implementation model;
    const struct arm_smmu_impl * impl;
    u32 num_context_banks;
    u32 num_s2_context_banks;
    long unsigned int[2] context_map;
    struct arm_smmu_cb * cbs;
    atomic_t irptndx;
    u32 num_mapping_groups;
    u16 streamid_mask;
    u16 smr_mask_mask;
    struct arm_smmu_smr * smrs;
    struct arm_smmu_s2cr * s2crs;
    struct mutex stream_map_mutex;
    long unsigned int va_size;
    long unsigned int ipa_size;
    long unsigned int pa_size;
    long unsigned int pgsize_bitmap;
    u32 num_global_irqs;
    u32 num_context_irqs;
    unsigned int * irqs;
    struct clk_bulk_data * clks;
    int num_clks;
    spinlock_t global_sync_lock;
    struct iommu_device iommu;
}
```
</details>
</li>
</ul>

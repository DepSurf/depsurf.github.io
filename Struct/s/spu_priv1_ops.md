# Struct: <code>spu_priv1_ops</code>

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
struct spu_priv1_ops {
    void (*)(struct spu *, int, u64) int_mask_and;
    void (*)(struct spu *, int, u64) int_mask_or;
    void (*)(struct spu *, int, u64) int_mask_set;
    u64 (*)(struct spu *, int) int_mask_get;
    void (*)(struct spu *, int, u64) int_stat_clear;
    u64 (*)(struct spu *, int) int_stat_get;
    void (*)(struct spu *, int) cpu_affinity_set;
    u64 (*)(struct spu *) mfc_dar_get;
    u64 (*)(struct spu *) mfc_dsisr_get;
    void (*)(struct spu *, u64) mfc_dsisr_set;
    void (*)(struct spu *) mfc_sdr_setup;
    void (*)(struct spu *, u64) mfc_sr1_set;
    u64 (*)(struct spu *) mfc_sr1_get;
    void (*)(struct spu *, u64) mfc_tclass_id_set;
    u64 (*)(struct spu *) mfc_tclass_id_get;
    void (*)(struct spu *) tlb_invalidate;
    void (*)(struct spu *, u64) resource_allocation_groupID_set;
    u64 (*)(struct spu *) resource_allocation_groupID_get;
    void (*)(struct spu *, u64) resource_allocation_enable_set;
    u64 (*)(struct spu *) resource_allocation_enable_get;
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
struct spu_priv1_ops {
    void (*)(struct spu *, int, u64) int_mask_and;
    void (*)(struct spu *, int, u64) int_mask_or;
    void (*)(struct spu *, int, u64) int_mask_set;
    u64 (*)(struct spu *, int) int_mask_get;
    void (*)(struct spu *, int, u64) int_stat_clear;
    u64 (*)(struct spu *, int) int_stat_get;
    void (*)(struct spu *, int) cpu_affinity_set;
    u64 (*)(struct spu *) mfc_dar_get;
    u64 (*)(struct spu *) mfc_dsisr_get;
    void (*)(struct spu *, u64) mfc_dsisr_set;
    void (*)(struct spu *) mfc_sdr_setup;
    void (*)(struct spu *, u64) mfc_sr1_set;
    u64 (*)(struct spu *) mfc_sr1_get;
    void (*)(struct spu *, u64) mfc_tclass_id_set;
    u64 (*)(struct spu *) mfc_tclass_id_get;
    void (*)(struct spu *) tlb_invalidate;
    void (*)(struct spu *, u64) resource_allocation_groupID_set;
    u64 (*)(struct spu *) resource_allocation_groupID_get;
    void (*)(struct spu *, u64) resource_allocation_enable_set;
    u64 (*)(struct spu *) resource_allocation_enable_get;
}
```
</details>
</li>
</ul>

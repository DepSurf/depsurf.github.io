# Struct: <code>kvm_pmu</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kvm_pmu {
    unsigned int nr_arch_gp_counters;
    unsigned int nr_arch_fixed_counters;
    unsigned int available_event_types;
    u64 fixed_ctr_ctrl;
    u64 global_ctrl;
    u64 global_status;
    u64 global_ovf_ctrl;
    u64[2] counter_bitmask;
    u64 global_ctrl_mask;
    u64 global_ovf_ctrl_mask;
    u64 reserved_bits;
    u8 version;
    struct kvm_pmc[32] gp_counters;
    struct kvm_pmc[4] fixed_counters;
    struct irq_work irq_work;
    long unsigned int[1] reprogram_pmi;
    long unsigned int[1] all_valid_pmc_idx;
    long unsigned int[1] pmc_in_use;
    bool need_cleanup;
    u8 event_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_pmu {
    unsigned int nr_arch_gp_counters;
    unsigned int nr_arch_fixed_counters;
    unsigned int available_event_types;
    u64 fixed_ctr_ctrl;
    u64 global_ctrl;
    u64 global_status;
    u64 global_ovf_ctrl;
    u64[2] counter_bitmask;
    u64 global_ctrl_mask;
    u64 global_ovf_ctrl_mask;
    u64 reserved_bits;
    u8 version;
    struct kvm_pmc[32] gp_counters;
    struct kvm_pmc[4] fixed_counters;
    struct irq_work irq_work;
    long unsigned int[1] reprogram_pmi;
    long unsigned int[1] all_valid_pmc_idx;
    long unsigned int[1] pmc_in_use;
    bool need_cleanup;
    u8 event_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_pmu {
    unsigned int nr_arch_gp_counters;
    unsigned int nr_arch_fixed_counters;
    unsigned int available_event_types;
    u64 fixed_ctr_ctrl;
    u64 global_ctrl;
    u64 global_status;
    u64 global_ovf_ctrl;
    u64[2] counter_bitmask;
    u64 global_ctrl_mask;
    u64 global_ovf_ctrl_mask;
    u64 reserved_bits;
    u8 version;
    struct kvm_pmc[32] gp_counters;
    struct kvm_pmc[4] fixed_counters;
    struct irq_work irq_work;
    long unsigned int[1] reprogram_pmi;
    long unsigned int[1] all_valid_pmc_idx;
    long unsigned int[1] pmc_in_use;
    bool need_cleanup;
    u8 event_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_pmu {
    unsigned int nr_arch_gp_counters;
    unsigned int nr_arch_fixed_counters;
    unsigned int available_event_types;
    u64 fixed_ctr_ctrl;
    u64 fixed_ctr_ctrl_mask;
    u64 global_ctrl;
    u64 global_status;
    u64[2] counter_bitmask;
    u64 global_ctrl_mask;
    u64 global_ovf_ctrl_mask;
    u64 reserved_bits;
    u64 raw_event_mask;
    u8 version;
    struct kvm_pmc[32] gp_counters;
    struct kvm_pmc[3] fixed_counters;
    struct irq_work irq_work;
    long unsigned int[1] reprogram_pmi;
    long unsigned int[1] all_valid_pmc_idx;
    long unsigned int[1] pmc_in_use;
    bool need_cleanup;
    u8 event_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_pmu {
    unsigned int nr_arch_gp_counters;
    unsigned int nr_arch_fixed_counters;
    unsigned int available_event_types;
    u64 fixed_ctr_ctrl;
    u64 fixed_ctr_ctrl_mask;
    u64 global_ctrl;
    u64 global_status;
    u64[2] counter_bitmask;
    u64 global_ctrl_mask;
    u64 global_ovf_ctrl_mask;
    u64 reserved_bits;
    u64 raw_event_mask;
    u8 version;
    struct kvm_pmc[8] gp_counters;
    struct kvm_pmc[3] fixed_counters;
    struct irq_work irq_work;
    long unsigned int[1] reprogram_pmi;
    atomic64_t __reprogram_pmi;
    long unsigned int[1] all_valid_pmc_idx;
    long unsigned int[1] pmc_in_use;
    u64 ds_area;
    u64 pebs_enable;
    u64 pebs_enable_mask;
    u64 pebs_data_cfg;
    u64 pebs_data_cfg_mask;
    u64 host_cross_mapped_mask;
    bool need_cleanup;
    u8 event_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_pmu {
    u8 version;
    unsigned int nr_arch_gp_counters;
    unsigned int nr_arch_fixed_counters;
    unsigned int available_event_types;
    u64 fixed_ctr_ctrl;
    u64 fixed_ctr_ctrl_mask;
    u64 global_ctrl;
    u64 global_status;
    u64[2] counter_bitmask;
    u64 global_ctrl_mask;
    u64 global_status_mask;
    u64 reserved_bits;
    u64 raw_event_mask;
    struct kvm_pmc[8] gp_counters;
    struct kvm_pmc[3] fixed_counters;
    struct irq_work irq_work;
    long unsigned int[1] reprogram_pmi;
    atomic64_t __reprogram_pmi;
    long unsigned int[1] all_valid_pmc_idx;
    long unsigned int[1] pmc_in_use;
    u64 ds_area;
    u64 pebs_enable;
    u64 pebs_enable_mask;
    u64 pebs_data_cfg;
    u64 pebs_data_cfg_mask;
    u64 host_cross_mapped_mask;
    bool need_cleanup;
    u8 event_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_pmu {
    u8 version;
    unsigned int nr_arch_gp_counters;
    unsigned int nr_arch_fixed_counters;
    unsigned int available_event_types;
    u64 fixed_ctr_ctrl;
    u64 fixed_ctr_ctrl_mask;
    u64 global_ctrl;
    u64 global_status;
    u64[2] counter_bitmask;
    u64 global_ctrl_mask;
    u64 global_status_mask;
    u64 reserved_bits;
    u64 raw_event_mask;
    struct kvm_pmc[8] gp_counters;
    struct kvm_pmc[3] fixed_counters;
    long unsigned int[1] reprogram_pmi;
    atomic64_t __reprogram_pmi;
    long unsigned int[1] all_valid_pmc_idx;
    long unsigned int[1] pmc_in_use;
    u64 ds_area;
    u64 pebs_enable;
    u64 pebs_enable_mask;
    u64 pebs_data_cfg;
    u64 pebs_data_cfg_mask;
    u64 host_cross_mapped_mask;
    bool need_cleanup;
    u8 event_count;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct kvm_pmu {
    int irq_num;
    struct kvm_pmc[32] pmc;
    long unsigned int[1] chained;
    bool ready;
    bool created;
    bool irq_level;
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct kvm_pmu {
    unsigned int nr_arch_gp_counters;
    unsigned int nr_arch_fixed_counters;
    unsigned int available_event_types;
    u64 fixed_ctr_ctrl;
    u64 global_ctrl;
    u64 global_status;
    u64 global_ovf_ctrl;
    u64[2] counter_bitmask;
    u64 global_ctrl_mask;
    u64 global_ovf_ctrl_mask;
    u64 reserved_bits;
    u8 version;
    struct kvm_pmc[32] gp_counters;
    struct kvm_pmc[4] fixed_counters;
    struct irq_work irq_work;
    long unsigned int[1] reprogram_pmi;
    long unsigned int[1] all_valid_pmc_idx;
    long unsigned int[1] pmc_in_use;
    bool need_cleanup;
    u8 event_count;
}
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 fixed_ctr_ctrl_mask</code>
</li>
<li>
<b>Field added. </b>
<code>u64 raw_event_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 global_ovf_ctrl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct kvm_pmc[4] fixed_counters</code> ➡️ <code>struct kvm_pmc[3] fixed_counters</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic64_t __reprogram_pmi</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ds_area</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pebs_enable</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pebs_enable_mask</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pebs_data_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pebs_data_cfg_mask</code>
</li>
<li>
<b>Field added. </b>
<code>u64 host_cross_mapped_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct kvm_pmc[32] gp_counters</code> ➡️ <code>struct kvm_pmc[8] gp_counters</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 global_status_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 global_ovf_ctrl_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct irq_work irq_work</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct kvm_pmu {
    int irq_num;
    struct kvm_pmc[32] pmc;
    long unsigned int[1] chained;
    bool ready;
    bool created;
    bool irq_level;
}
```
</details>
</li>
</ul>

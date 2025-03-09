# Struct: <code>intel_uncore_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int mmio_map_size;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    const struct attribute_group * * attr_update;
    struct pmu * pmu;
    u64 * topology;
    int (*)(struct intel_uncore_type *) set_mapping;
    void (*)(struct intel_uncore_type *) cleanup_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    int type_id;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    u64 * box_ctls;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int mmio_map_size;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    unsigned int * pci_offsets;
    unsigned int * mmio_offsets;
    unsigned int * box_ids;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    const struct attribute_group * * attr_update;
    struct pmu * pmu;
    struct intel_uncore_topology * topology;
    int (*)(struct intel_uncore_type *) set_mapping;
    void (*)(struct intel_uncore_type *) cleanup_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    int type_id;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    u64 * box_ctls;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int mmio_map_size;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    unsigned int * pci_offsets;
    unsigned int * mmio_offsets;
    unsigned int * box_ids;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    const struct attribute_group * * attr_update;
    struct pmu * pmu;
    struct intel_uncore_topology * topology;
    int (*)(struct intel_uncore_type *) get_topology;
    int (*)(struct intel_uncore_type *) set_mapping;
    void (*)(struct intel_uncore_type *) cleanup_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    int type_id;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    u64 * box_ctls;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int mmio_map_size;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    unsigned int * pci_offsets;
    unsigned int * mmio_offsets;
    unsigned int * box_ids;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    const struct attribute_group * * attr_update;
    struct pmu * pmu;
    struct intel_uncore_topology * topology;
    int (*)(struct intel_uncore_type *) get_topology;
    int (*)(struct intel_uncore_type *) set_mapping;
    void (*)(struct intel_uncore_type *) cleanup_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    int type_id;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    u64 * box_ctls;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int mmio_map_size;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    unsigned int * pci_offsets;
    unsigned int * mmio_offsets;
    unsigned int * box_ids;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    const struct attribute_group * * attr_update;
    struct pmu * pmu;
    struct intel_uncore_topology * * topology;
    int (*)(struct intel_uncore_type *) get_topology;
    void (*)(struct intel_uncore_type *) set_mapping;
    void (*)(struct intel_uncore_type *) cleanup_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    int type_id;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    u64 * box_ctls;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int mmio_map_size;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    unsigned int * pci_offsets;
    unsigned int * mmio_offsets;
    unsigned int * box_ids;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    const struct attribute_group * * attr_update;
    struct pmu * pmu;
    struct intel_uncore_topology * * topology;
    int (*)(struct intel_uncore_type *) get_topology;
    void (*)(struct intel_uncore_type *) set_mapping;
    void (*)(struct intel_uncore_type *) cleanup_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    int type_id;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    u64 * box_ctls;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int mmio_map_size;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    u64 * msr_offsets;
    u64 * pci_offsets;
    u64 * mmio_offsets;
    unsigned int * box_ids;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    const struct attribute_group * * attr_update;
    struct pmu * pmu;
    struct intel_uncore_topology * * topology;
    int (*)(struct intel_uncore_type *) get_topology;
    void (*)(struct intel_uncore_type *) set_mapping;
    void (*)(struct intel_uncore_type *) cleanup_mapping;
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
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int event_mask_ext</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int num_freerunning_types</code>
</li>
<li>
<b>Field added. </b>
<code>struct freerunning_counters * freerunning</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int mmio_offset</code>
</li>
</ul>
</details>
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
<code>unsigned int mmio_map_size</code>
</li>
<li>
<b>Field added. </b>
<code>const struct attribute_group * * attr_update</code>
</li>
<li>
<b>Field added. </b>
<code>u64 * topology</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct intel_uncore_type *) set_mapping</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct intel_uncore_type *) cleanup_mapping</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int type_id</code>
</li>
<li>
<b>Field added. </b>
<code>u64 * box_ctls</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int * pci_offsets</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int * mmio_offsets</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int * box_ids</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 * topology</code> ➡️ <code>struct intel_uncore_topology * topology</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct intel_uncore_type *) get_topology</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct intel_uncore_topology * topology</code> ➡️ <code>struct intel_uncore_topology * * topology</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct intel_uncore_type *) set_mapping</code> ➡️ <code>void (*)(struct intel_uncore_type *) set_mapping</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int * msr_offsets</code> ➡️ <code>u64 * msr_offsets</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int * pci_offsets</code> ➡️ <code>u64 * pci_offsets</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int * mmio_offsets</code> ➡️ <code>u64 * mmio_offsets</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct intel_uncore_type {
    const char * name;
    int num_counters;
    int num_boxes;
    int perf_ctr_bits;
    int fixed_ctr_bits;
    int num_freerunning_types;
    unsigned int perf_ctr;
    unsigned int event_ctl;
    unsigned int event_mask;
    unsigned int event_mask_ext;
    unsigned int fixed_ctr;
    unsigned int fixed_ctl;
    unsigned int box_ctl;
    unsigned int msr_offset;
    unsigned int mmio_offset;
    unsigned int num_shared_regs;
    unsigned int single_fixed;
    unsigned int pair_ctr_ctl;
    unsigned int * msr_offsets;
    struct event_constraint unconstrainted;
    struct event_constraint * constraints;
    struct intel_uncore_pmu * pmus;
    struct intel_uncore_ops * ops;
    struct uncore_event_desc * event_descs;
    struct freerunning_counters * freerunning;
    const struct attribute_group *[4] attr_groups;
    struct pmu * pmu;
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

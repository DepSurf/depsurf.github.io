# Struct: <code>cpu_spec</code>

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
struct cpu_spec {
    unsigned int pvr_mask;
    unsigned int pvr_value;
    char * cpu_name;
    long unsigned int cpu_features;
    unsigned int cpu_user_features;
    unsigned int cpu_user_features2;
    unsigned int mmu_features;
    unsigned int icache_bsize;
    unsigned int dcache_bsize;
    void (*)() cpu_down_flush;
    unsigned int num_pmcs;
    enum powerpc_pmc_type pmc_type;
    cpu_setup_t cpu_setup;
    cpu_restore_t cpu_restore;
    char * oprofile_cpu_type;
    enum powerpc_oprofile_type oprofile_type;
    long unsigned int oprofile_mmcra_sihv;
    long unsigned int oprofile_mmcra_sipr;
    long unsigned int oprofile_mmcra_clear;
    char * platform;
    int (*)(struct pt_regs *) machine_check;
    long int (*)(struct pt_regs *) machine_check_early;
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
struct cpu_spec {
    unsigned int pvr_mask;
    unsigned int pvr_value;
    char * cpu_name;
    long unsigned int cpu_features;
    unsigned int cpu_user_features;
    unsigned int cpu_user_features2;
    unsigned int mmu_features;
    unsigned int icache_bsize;
    unsigned int dcache_bsize;
    void (*)() cpu_down_flush;
    unsigned int num_pmcs;
    enum powerpc_pmc_type pmc_type;
    cpu_setup_t cpu_setup;
    cpu_restore_t cpu_restore;
    char * oprofile_cpu_type;
    enum powerpc_oprofile_type oprofile_type;
    long unsigned int oprofile_mmcra_sihv;
    long unsigned int oprofile_mmcra_sipr;
    long unsigned int oprofile_mmcra_clear;
    char * platform;
    int (*)(struct pt_regs *) machine_check;
    long int (*)(struct pt_regs *) machine_check_early;
}
```
</details>
</li>
</ul>

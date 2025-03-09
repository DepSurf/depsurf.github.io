# Struct: <code>cpuinfo_x86</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_mask;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[17] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u8 compute_unit_id;
    u16 cpu_index;
    u32 microcode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_mask;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[19] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_index;
    u32 microcode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_mask;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[19] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_index;
    u32 microcode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_mask;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[19] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_index;
    u32 microcode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_index;
    u32 microcode;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u32[3] vmx_capability;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    long unsigned int x86_capability_alignment;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_cache_mbm_width_offset;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u32[3] vmx_capability;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    long unsigned int x86_capability_alignment;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_cache_mbm_width_offset;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u32[3] vmx_capability;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[21] x86_capability;
    long unsigned int x86_capability_alignment;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_cache_mbm_width_offset;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u32[3] vmx_capability;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[21] x86_capability;
    long unsigned int x86_capability_alignment;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_cache_mbm_width_offset;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    bool smt_active;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u32[3] vmx_capability;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[21] x86_capability;
    long unsigned int x86_capability_alignment;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_cache_mbm_width_offset;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u64 ppin;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    bool smt_active;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u32[5] vmx_capability;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[21] x86_capability;
    long unsigned int x86_capability_alignment;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_cache_mbm_width_offset;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u64 ppin;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    bool smt_active;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u32[5] vmx_capability;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[23] x86_capability;
    long unsigned int x86_capability_alignment;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_cache_mbm_width_offset;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u64 ppin;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    bool smt_active;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u32[5] vmx_capability;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[24] x86_capability;
    long unsigned int x86_capability_alignment;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    struct cpuinfo_topology topo;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_cache_mbm_width_offset;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u64 ppin;
    u16 x86_max_cores;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 cpu_index;
    bool smt_active;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
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
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
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
<b>Field removed. </b>
<code>u8 compute_unit_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[17] x86_capability</code> ➡️ <code>__u32[19] x86_capability</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 cu_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 x86_stepping</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 x86_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[19] x86_capability</code> ➡️ <code>__u32[20] x86_capability</code>
</li>
<li>
<b>Field type changed. </b>
<code>int x86_cache_size</code> ➡️ <code>unsigned int x86_cache_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 x86_cache_bits</code>
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
<code>u16 cpu_die_id</code>
</li>
<li>
<b>Field added. </b>
<code>u16 logical_die_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32[3] vmx_capability</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int x86_capability_alignment</code>
</li>
<li>
<b>Field added. </b>
<code>int x86_cache_mbm_width_offset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__u32[20] x86_capability</code> ➡️ <code>__u32[21] x86_capability</code>
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
<code>bool smt_active</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 ppin</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__u32[3] vmx_capability</code> ➡️ <code>__u32[5] vmx_capability</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__u32[21] x86_capability</code> ➡️ <code>__u32[23] x86_capability</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cpuinfo_topology topo</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 cu_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 apicid</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 initial_apicid</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 phys_proc_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 logical_proc_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 cpu_core_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 cpu_die_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 logical_die_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[23] x86_capability</code> ➡️ <code>__u32[24] x86_capability</code>
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
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpuinfo_x86 {
    __u8 x86;
    __u8 x86_vendor;
    __u8 x86_model;
    __u8 x86_stepping;
    int x86_tlbsize;
    __u8 x86_virt_bits;
    __u8 x86_phys_bits;
    __u8 x86_coreid_bits;
    __u8 cu_id;
    __u32 extended_cpuid_level;
    int cpuid_level;
    __u32[20] x86_capability;
    char[16] x86_vendor_id;
    char[64] x86_model_id;
    unsigned int x86_cache_size;
    int x86_cache_alignment;
    int x86_cache_max_rmid;
    int x86_cache_occ_scale;
    int x86_power;
    long unsigned int loops_per_jiffy;
    u16 x86_max_cores;
    u16 apicid;
    u16 initial_apicid;
    u16 x86_clflush_size;
    u16 booted_cores;
    u16 phys_proc_id;
    u16 logical_proc_id;
    u16 cpu_core_id;
    u16 cpu_die_id;
    u16 logical_die_id;
    u16 cpu_index;
    u32 microcode;
    u8 x86_cache_bits;
    unsigned int initialized;
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

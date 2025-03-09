# Struct: <code>fw_dump</code>

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
struct fw_dump {
    long unsigned int reserve_dump_area_start;
    long unsigned int reserve_dump_area_size;
    long unsigned int reserve_bootvar;
    long unsigned int cpu_state_data_size;
    u64 cpu_state_dest_vaddr;
    u32 cpu_state_data_version;
    u32 cpu_state_entry_size;
    long unsigned int hpte_region_size;
    long unsigned int boot_memory_size;
    u64 boot_mem_dest_addr;
    u64[128] boot_mem_addr;
    u64[128] boot_mem_sz;
    u64 boot_mem_top;
    u64 boot_mem_regs_cnt;
    long unsigned int fadumphdr_addr;
    long unsigned int cpu_notes_buf_vaddr;
    long unsigned int cpu_notes_buf_size;
    u64 max_copy_size;
    u64 kernel_metadata;
    int ibm_configure_kernel_dump;
    long unsigned int fadump_enabled;
    long unsigned int fadump_supported;
    long unsigned int dump_active;
    long unsigned int dump_registered;
    long unsigned int nocma;
    struct fadump_ops * ops;
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
struct fw_dump {
    long unsigned int reserve_dump_area_start;
    long unsigned int reserve_dump_area_size;
    long unsigned int reserve_bootvar;
    long unsigned int cpu_state_data_size;
    u64 cpu_state_dest_vaddr;
    u32 cpu_state_data_version;
    u32 cpu_state_entry_size;
    long unsigned int hpte_region_size;
    long unsigned int boot_memory_size;
    u64 boot_mem_dest_addr;
    u64[128] boot_mem_addr;
    u64[128] boot_mem_sz;
    u64 boot_mem_top;
    u64 boot_mem_regs_cnt;
    long unsigned int fadumphdr_addr;
    long unsigned int cpu_notes_buf_vaddr;
    long unsigned int cpu_notes_buf_size;
    u64 max_copy_size;
    u64 kernel_metadata;
    int ibm_configure_kernel_dump;
    long unsigned int fadump_enabled;
    long unsigned int fadump_supported;
    long unsigned int dump_active;
    long unsigned int dump_registered;
    long unsigned int nocma;
    struct fadump_ops * ops;
}
```
</details>
</li>
</ul>

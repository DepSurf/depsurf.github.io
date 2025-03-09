# Struct: <code>ramoops_context</code>

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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ramoops_context {
    struct persistent_ram_zone * * dprzs;
    struct persistent_ram_zone * cprz;
    struct persistent_ram_zone * * fprzs;
    struct persistent_ram_zone * mprz;
    phys_addr_t phys_addr;
    long unsigned int size;
    unsigned int memtype;
    size_t record_size;
    size_t console_size;
    size_t ftrace_size;
    size_t pmsg_size;
    int dump_oops;
    u32 flags;
    struct persistent_ram_ecc_info ecc_info;
    unsigned int max_dump_cnt;
    unsigned int dump_write_cnt;
    unsigned int dump_read_cnt;
    unsigned int console_read_cnt;
    unsigned int max_ftrace_cnt;
    unsigned int ftrace_read_cnt;
    unsigned int pmsg_read_cnt;
    struct pstore_info pstore;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct ramoops_context {
    struct persistent_ram_zone * * dprzs;
    struct persistent_ram_zone * cprz;
    struct persistent_ram_zone * * fprzs;
    struct persistent_ram_zone * mprz;
    phys_addr_t phys_addr;
    long unsigned int size;
    unsigned int memtype;
    size_t record_size;
    size_t console_size;
    size_t ftrace_size;
    size_t pmsg_size;
    int dump_oops;
    u32 flags;
    struct persistent_ram_ecc_info ecc_info;
    unsigned int max_dump_cnt;
    unsigned int dump_write_cnt;
    unsigned int dump_read_cnt;
    unsigned int console_read_cnt;
    unsigned int max_ftrace_cnt;
    unsigned int ftrace_read_cnt;
    unsigned int pmsg_read_cnt;
    struct pstore_info pstore;
}
```
</details>
</li>
</ul>

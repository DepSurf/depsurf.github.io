# Struct: <code>lppaca</code>

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
struct lppaca {
    __be32 desc;
    __be16 size;
    u8[3] reserved1;
    u8 __old_status;
    u8[14] reserved3;
    volatile __be32 dyn_hw_node_id;
    volatile __be32 dyn_hw_proc_id;
    u8[56] reserved4;
    volatile volatile u8[8] vphn_assoc_counts;
    u8[32] reserved5;
    u8[48] reserved6;
    u8 cede_latency_hint;
    u8 ebb_regs_in_use;
    u8[6] reserved7;
    u8 dtl_enable_mask;
    u8 donate_dedicated_cpu;
    u8 fpregs_in_use;
    u8 pmcregs_in_use;
    u8[28] reserved8;
    __be64 wait_state_cycles;
    u8[28] reserved9;
    __be16 slb_count;
    u8 idle;
    u8 vmxregs_in_use;
    volatile __be32 yield_count;
    volatile __be32 dispersion_count;
    volatile __be64 cmo_faults;
    volatile __be64 cmo_fault_time;
    u8[104] reserved10;
    __be32 page_ins;
    u8[148] reserved11;
    volatile __be64 dtl_idx;
    u8[96] reserved12;
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
struct lppaca {
    __be32 desc;
    __be16 size;
    u8[3] reserved1;
    u8 __old_status;
    u8[14] reserved3;
    volatile __be32 dyn_hw_node_id;
    volatile __be32 dyn_hw_proc_id;
    u8[56] reserved4;
    volatile volatile u8[8] vphn_assoc_counts;
    u8[32] reserved5;
    u8[48] reserved6;
    u8 cede_latency_hint;
    u8 ebb_regs_in_use;
    u8[6] reserved7;
    u8 dtl_enable_mask;
    u8 donate_dedicated_cpu;
    u8 fpregs_in_use;
    u8 pmcregs_in_use;
    u8[28] reserved8;
    __be64 wait_state_cycles;
    u8[28] reserved9;
    __be16 slb_count;
    u8 idle;
    u8 vmxregs_in_use;
    volatile __be32 yield_count;
    volatile __be32 dispersion_count;
    volatile __be64 cmo_faults;
    volatile __be64 cmo_fault_time;
    u8[104] reserved10;
    __be32 page_ins;
    u8[148] reserved11;
    volatile __be64 dtl_idx;
    u8[96] reserved12;
}
```
</details>
</li>
</ul>

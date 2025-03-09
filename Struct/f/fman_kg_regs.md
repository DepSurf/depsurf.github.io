# Struct: <code>fman_kg_regs</code>

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
struct fman_kg_regs {
    u32 fmkg_gcr;
    u32 res004;
    u32 res008;
    u32 fmkg_eer;
    u32 fmkg_eeer;
    u32 res014;
    u32 res018;
    u32 fmkg_seer;
    u32 fmkg_seeer;
    u32 fmkg_gsr;
    u32 fmkg_tpc;
    u32 fmkg_serc;
    u32[4] res030;
    u32 fmkg_fdor;
    u32 fmkg_gdv0r;
    u32 fmkg_gdv1r;
    u32[6] res04c;
    u32 fmkg_feer;
    u32[38] res068;
    u32[63] fmkg_indirect;
    struct fman_kg_scheme_regs fmkg_sch;
    struct fman_kg_pe_regs fmkg_pe;
    u32 fmkg_ar;
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
struct fman_kg_regs {
    u32 fmkg_gcr;
    u32 res004;
    u32 res008;
    u32 fmkg_eer;
    u32 fmkg_eeer;
    u32 res014;
    u32 res018;
    u32 fmkg_seer;
    u32 fmkg_seeer;
    u32 fmkg_gsr;
    u32 fmkg_tpc;
    u32 fmkg_serc;
    u32[4] res030;
    u32 fmkg_fdor;
    u32 fmkg_gdv0r;
    u32 fmkg_gdv1r;
    u32[6] res04c;
    u32 fmkg_feer;
    u32[38] res068;
    u32[63] fmkg_indirect;
    struct fman_kg_scheme_regs fmkg_sch;
    struct fman_kg_pe_regs fmkg_pe;
    u32 fmkg_ar;
}
```
</details>
</li>
</ul>

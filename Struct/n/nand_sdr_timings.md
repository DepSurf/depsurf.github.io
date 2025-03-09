# Struct: <code>nand_sdr_timings</code>

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
struct nand_sdr_timings {
    u64 tBERS_max;
    u32 tCCS_min;
    u64 tPROG_max;
    u64 tR_max;
    u32 tALH_min;
    u32 tADL_min;
    u32 tALS_min;
    u32 tAR_min;
    u32 tCEA_max;
    u32 tCEH_min;
    u32 tCH_min;
    u32 tCHZ_max;
    u32 tCLH_min;
    u32 tCLR_min;
    u32 tCLS_min;
    u32 tCOH_min;
    u32 tCS_min;
    u32 tDH_min;
    u32 tDS_min;
    u32 tFEAT_max;
    u32 tIR_min;
    u32 tITC_max;
    u32 tRC_min;
    u32 tREA_max;
    u32 tREH_min;
    u32 tRHOH_min;
    u32 tRHW_min;
    u32 tRHZ_max;
    u32 tRLOH_min;
    u32 tRP_min;
    u32 tRR_min;
    u64 tRST_max;
    u32 tWB_max;
    u32 tWC_min;
    u32 tWH_min;
    u32 tWHR_min;
    u32 tWP_min;
    u32 tWW_min;
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
struct nand_sdr_timings {
    u64 tBERS_max;
    u32 tCCS_min;
    u64 tPROG_max;
    u64 tR_max;
    u32 tALH_min;
    u32 tADL_min;
    u32 tALS_min;
    u32 tAR_min;
    u32 tCEA_max;
    u32 tCEH_min;
    u32 tCH_min;
    u32 tCHZ_max;
    u32 tCLH_min;
    u32 tCLR_min;
    u32 tCLS_min;
    u32 tCOH_min;
    u32 tCS_min;
    u32 tDH_min;
    u32 tDS_min;
    u32 tFEAT_max;
    u32 tIR_min;
    u32 tITC_max;
    u32 tRC_min;
    u32 tREA_max;
    u32 tREH_min;
    u32 tRHOH_min;
    u32 tRHW_min;
    u32 tRHZ_max;
    u32 tRLOH_min;
    u32 tRP_min;
    u32 tRR_min;
    u64 tRST_max;
    u32 tWB_max;
    u32 tWC_min;
    u32 tWH_min;
    u32 tWHR_min;
    u32 tWP_min;
    u32 tWW_min;
}
```
</details>
</li>
</ul>

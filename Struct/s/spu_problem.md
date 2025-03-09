# Struct: <code>spu_problem</code>

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
struct spu_problem {
    u64 spc_mssync_RW;
    u8[12280] pad_0x0008_0x3000;
    u8[4] pad_0x3000_0x3004;
    u32 mfc_lsa_W;
    u64 mfc_ea_W;
    union mfc_tag_size_class_cmd mfc_union_W;
    u8[236] pad_0x3018_0x3104;
    u32 dma_qstatus_R;
    u8[252] pad_0x3108_0x3204;
    u32 dma_querytype_RW;
    u8[20] pad_0x3208_0x321c;
    u32 dma_querymask_RW;
    u8[12] pad_0x3220_0x322c;
    u32 dma_tagstatus_R;
    u8[3536] pad_0x3230_0x4000;
    u8[4] pad_0x4000_0x4004;
    u32 pu_mb_R;
    u8[4] pad_0x4008_0x400c;
    u32 spu_mb_W;
    u8[4] pad_0x4010_0x4014;
    u32 mb_stat_R;
    u8[4] pad_0x4018_0x401c;
    u32 spu_runcntl_RW;
    u8[4] pad_0x4020_0x4024;
    u32 spu_status_R;
    u8[4] pad_0x4028_0x402c;
    u32 spu_spe_R;
    u8[4] pad_0x4030_0x4034;
    u32 spu_npc_RW;
    u8[65480] pad_0x4038_0x14000;
    u8[12] pad_0x14000_0x1400c;
    u32 signal_notify1;
    u8[32764] pad_0x14010_0x1c00c;
    u32 signal_notify2;
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
struct spu_problem {
    u64 spc_mssync_RW;
    u8[12280] pad_0x0008_0x3000;
    u8[4] pad_0x3000_0x3004;
    u32 mfc_lsa_W;
    u64 mfc_ea_W;
    union mfc_tag_size_class_cmd mfc_union_W;
    u8[236] pad_0x3018_0x3104;
    u32 dma_qstatus_R;
    u8[252] pad_0x3108_0x3204;
    u32 dma_querytype_RW;
    u8[20] pad_0x3208_0x321c;
    u32 dma_querymask_RW;
    u8[12] pad_0x3220_0x322c;
    u32 dma_tagstatus_R;
    u8[3536] pad_0x3230_0x4000;
    u8[4] pad_0x4000_0x4004;
    u32 pu_mb_R;
    u8[4] pad_0x4008_0x400c;
    u32 spu_mb_W;
    u8[4] pad_0x4010_0x4014;
    u32 mb_stat_R;
    u8[4] pad_0x4018_0x401c;
    u32 spu_runcntl_RW;
    u8[4] pad_0x4020_0x4024;
    u32 spu_status_R;
    u8[4] pad_0x4028_0x402c;
    u32 spu_spe_R;
    u8[4] pad_0x4030_0x4034;
    u32 spu_npc_RW;
    u8[65480] pad_0x4038_0x14000;
    u8[12] pad_0x14000_0x1400c;
    u32 signal_notify1;
    u8[32764] pad_0x14010_0x1c00c;
    u32 signal_notify2;
}
```
</details>
</li>
</ul>

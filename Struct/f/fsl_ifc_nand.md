# Struct: <code>fsl_ifc_nand</code>

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
struct fsl_ifc_nand {
    __be32 ncfgr;
    u32[4] res1;
    __be32 nand_fcr0;
    __be32 nand_fcr1;
    u32[8] res2;
    __be32 row0;
    u32 res3;
    __be32 col0;
    u32 res4;
    __be32 row1;
    u32 res5;
    __be32 col1;
    u32 res6;
    __be32 row2;
    u32 res7;
    __be32 col2;
    u32 res8;
    __be32 row3;
    u32 res9;
    __be32 col3;
    u32[36] res10;
    __be32 nand_fbcr;
    u32 res11;
    __be32 nand_fir0;
    __be32 nand_fir1;
    __be32 nand_fir2;
    u32[16] res12;
    __be32 nand_csel;
    u32 res13;
    __be32 nandseq_strt;
    u32 res14;
    __be32 nand_evter_stat;
    u32 res15;
    __be32 pgrdcmpl_evt_stat;
    u32[2] res16;
    __be32 nand_evter_en;
    u32[2] res17;
    __be32 nand_evter_intr_en;
    __be32 nand_vol_addr_stat;
    u32 res18;
    __be32 nand_erattr0;
    __be32 nand_erattr1;
    u32[16] res19;
    __be32 nand_fsr;
    u32 res20;
    __be32[8] nand_eccstat;
    u32[28] res21;
    __be32 nanndcr;
    u32[2] res22;
    __be32 nand_autoboot_trgr;
    u32 res23;
    __be32 nand_mdr;
    u32[28] res24;
    __be32 nand_dll_lowcfg0;
    __be32 nand_dll_lowcfg1;
    u32 res25;
    __be32 nand_dll_lowstat;
    u32[60] res26;
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
struct fsl_ifc_nand {
    __be32 ncfgr;
    u32[4] res1;
    __be32 nand_fcr0;
    __be32 nand_fcr1;
    u32[8] res2;
    __be32 row0;
    u32 res3;
    __be32 col0;
    u32 res4;
    __be32 row1;
    u32 res5;
    __be32 col1;
    u32 res6;
    __be32 row2;
    u32 res7;
    __be32 col2;
    u32 res8;
    __be32 row3;
    u32 res9;
    __be32 col3;
    u32[36] res10;
    __be32 nand_fbcr;
    u32 res11;
    __be32 nand_fir0;
    __be32 nand_fir1;
    __be32 nand_fir2;
    u32[16] res12;
    __be32 nand_csel;
    u32 res13;
    __be32 nandseq_strt;
    u32 res14;
    __be32 nand_evter_stat;
    u32 res15;
    __be32 pgrdcmpl_evt_stat;
    u32[2] res16;
    __be32 nand_evter_en;
    u32[2] res17;
    __be32 nand_evter_intr_en;
    __be32 nand_vol_addr_stat;
    u32 res18;
    __be32 nand_erattr0;
    __be32 nand_erattr1;
    u32[16] res19;
    __be32 nand_fsr;
    u32 res20;
    __be32[8] nand_eccstat;
    u32[28] res21;
    __be32 nanndcr;
    u32[2] res22;
    __be32 nand_autoboot_trgr;
    u32 res23;
    __be32 nand_mdr;
    u32[28] res24;
    __be32 nand_dll_lowcfg0;
    __be32 nand_dll_lowcfg1;
    u32 res25;
    __be32 nand_dll_lowstat;
    u32[60] res26;
}
```
</details>
</li>
</ul>

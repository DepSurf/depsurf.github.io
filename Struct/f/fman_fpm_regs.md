# Struct: <code>fman_fpm_regs</code>

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
struct fman_fpm_regs {
    u32 fmfp_tnc;
    u32 fmfp_prc;
    u32 fmfp_brkc;
    u32 fmfp_mxd;
    u32 fmfp_dist1;
    u32 fmfp_dist2;
    u32 fm_epi;
    u32 fm_rie;
    u32[4] fmfp_fcev;
    u32[4] res0030;
    u32[4] fmfp_cee;
    u32[4] res0050;
    u32 fmfp_tsc1;
    u32 fmfp_tsc2;
    u32 fmfp_tsp;
    u32 fmfp_tsf;
    u32 fm_rcr;
    u32 fmfp_extc;
    u32 fmfp_ext1;
    u32 fmfp_ext2;
    u32[16] fmfp_drd;
    u32 fmfp_dra;
    u32 fm_ip_rev_1;
    u32 fm_ip_rev_2;
    u32 fm_rstc;
    u32 fm_cld;
    u32 fm_npi;
    u32 fmfp_exte;
    u32 fmfp_ee;
    u32[4] fmfp_cev;
    u32[4] res00f0;
    u32[50] fmfp_ps;
    u32[14] res01c8;
    u32 fmfp_clfabc;
    u32 fmfp_clfcc;
    u32 fmfp_clfaval;
    u32 fmfp_clfbval;
    u32 fmfp_clfcval;
    u32 fmfp_clfamsk;
    u32 fmfp_clfbmsk;
    u32 fmfp_clfcmsk;
    u32 fmfp_clfamc;
    u32 fmfp_clfbmc;
    u32 fmfp_clfcmc;
    u32 fmfp_decceh;
    u32[116] res0230;
    u32[128] fmfp_ts;
    u32[640] res0600;
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
struct fman_fpm_regs {
    u32 fmfp_tnc;
    u32 fmfp_prc;
    u32 fmfp_brkc;
    u32 fmfp_mxd;
    u32 fmfp_dist1;
    u32 fmfp_dist2;
    u32 fm_epi;
    u32 fm_rie;
    u32[4] fmfp_fcev;
    u32[4] res0030;
    u32[4] fmfp_cee;
    u32[4] res0050;
    u32 fmfp_tsc1;
    u32 fmfp_tsc2;
    u32 fmfp_tsp;
    u32 fmfp_tsf;
    u32 fm_rcr;
    u32 fmfp_extc;
    u32 fmfp_ext1;
    u32 fmfp_ext2;
    u32[16] fmfp_drd;
    u32 fmfp_dra;
    u32 fm_ip_rev_1;
    u32 fm_ip_rev_2;
    u32 fm_rstc;
    u32 fm_cld;
    u32 fm_npi;
    u32 fmfp_exte;
    u32 fmfp_ee;
    u32[4] fmfp_cev;
    u32[4] res00f0;
    u32[50] fmfp_ps;
    u32[14] res01c8;
    u32 fmfp_clfabc;
    u32 fmfp_clfcc;
    u32 fmfp_clfaval;
    u32 fmfp_clfbval;
    u32 fmfp_clfcval;
    u32 fmfp_clfamsk;
    u32 fmfp_clfbmsk;
    u32 fmfp_clfcmsk;
    u32 fmfp_clfamc;
    u32 fmfp_clfbmc;
    u32 fmfp_clfcmc;
    u32 fmfp_decceh;
    u32[116] res0230;
    u32[128] fmfp_ts;
    u32[640] res0600;
}
```
</details>
</li>
</ul>

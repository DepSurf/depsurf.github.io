# Struct: <code>fman_bmi_regs</code>

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
struct fman_bmi_regs {
    u32 fmbm_init;
    u32 fmbm_cfg1;
    u32 fmbm_cfg2;
    u32[5] res000c;
    u32 fmbm_ievr;
    u32 fmbm_ier;
    u32 fmbm_ifr;
    u32[5] res002c;
    u32[8] fmbm_arb;
    u32[12] res0060;
    u32[3] fmbm_dtc;
    u32 res009c;
    u32[12] fmbm_dcv;
    u32[12] fmbm_dcm;
    u32 fmbm_gde;
    u32[63] fmbm_pp;
    u32 res0200;
    u32[63] fmbm_pfs;
    u32 res0300;
    u32[63] fmbm_spliodn;
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
struct fman_bmi_regs {
    u32 fmbm_init;
    u32 fmbm_cfg1;
    u32 fmbm_cfg2;
    u32[5] res000c;
    u32 fmbm_ievr;
    u32 fmbm_ier;
    u32 fmbm_ifr;
    u32[5] res002c;
    u32[8] fmbm_arb;
    u32[12] res0060;
    u32[3] fmbm_dtc;
    u32 res009c;
    u32[12] fmbm_dcv;
    u32[12] fmbm_dcm;
    u32 fmbm_gde;
    u32[63] fmbm_pp;
    u32 res0200;
    u32[63] fmbm_pfs;
    u32 res0300;
    u32[63] fmbm_spliodn;
}
```
</details>
</li>
</ul>

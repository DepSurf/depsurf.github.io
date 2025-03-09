# Struct: <code>fsl_lbc_regs</code>

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
struct fsl_lbc_regs {
    struct fsl_lbc_bank[12] bank;
    u8[8] res0;
    __be32 mar;
    u8[4] res1;
    __be32 mamr;
    __be32 mbmr;
    __be32 mcmr;
    u8[8] res2;
    __be32 mrtpr;
    __be32 mdr;
    u8[4] res3;
    __be32 lsor;
    __be32 lsdmr;
    u8[8] res4;
    __be32 lurt;
    __be32 lsrt;
    u8[8] res5;
    __be32 ltesr;
    __be32 ltedr;
    __be32 lteir;
    __be32 lteatr;
    __be32 ltear;
    __be32 lteccr;
    u8[8] res6;
    __be32 lbcr;
    __be32 lcrr;
    u8[8] res7;
    __be32 fmr;
    __be32 fir;
    __be32 fcr;
    __be32 fbar;
    __be32 fpar;
    __be32 fbcr;
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
struct fsl_lbc_regs {
    struct fsl_lbc_bank[12] bank;
    u8[8] res0;
    __be32 mar;
    u8[4] res1;
    __be32 mamr;
    __be32 mbmr;
    __be32 mcmr;
    u8[8] res2;
    __be32 mrtpr;
    __be32 mdr;
    u8[4] res3;
    __be32 lsor;
    __be32 lsdmr;
    u8[8] res4;
    __be32 lurt;
    __be32 lsrt;
    u8[8] res5;
    __be32 ltesr;
    __be32 ltedr;
    __be32 lteir;
    __be32 lteatr;
    __be32 ltear;
    __be32 lteccr;
    u8[8] res6;
    __be32 lbcr;
    __be32 lcrr;
    u8[8] res7;
    __be32 fmr;
    __be32 fir;
    __be32 fcr;
    __be32 fbar;
    __be32 fpar;
    __be32 fbcr;
}
```
</details>
</li>
</ul>

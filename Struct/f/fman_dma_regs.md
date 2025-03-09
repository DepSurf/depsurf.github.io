# Struct: <code>fman_dma_regs</code>

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
struct fman_dma_regs {
    u32 fmdmsr;
    u32 fmdmmr;
    u32 fmdmtr;
    u32 fmdmhy;
    u32 fmdmsetr;
    u32 fmdmtah;
    u32 fmdmtal;
    u32 fmdmtcid;
    u32 fmdmra;
    u32 fmdmrd;
    u32 fmdmwcr;
    u32 fmdmebcr;
    u32 fmdmccqdr;
    u32 fmdmccqvr1;
    u32 fmdmccqvr2;
    u32 fmdmcqvr3;
    u32 fmdmcqvr4;
    u32 fmdmcqvr5;
    u32 fmdmsefrc;
    u32 fmdmsqfrc;
    u32 fmdmssrc;
    u32 fmdmdcr;
    u32 fmdmemsr;
    u32 res005c;
    u32[32] fmdmplr;
    u32[968] res00e0;
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
struct fman_dma_regs {
    u32 fmdmsr;
    u32 fmdmmr;
    u32 fmdmtr;
    u32 fmdmhy;
    u32 fmdmsetr;
    u32 fmdmtah;
    u32 fmdmtal;
    u32 fmdmtcid;
    u32 fmdmra;
    u32 fmdmrd;
    u32 fmdmwcr;
    u32 fmdmebcr;
    u32 fmdmccqdr;
    u32 fmdmccqvr1;
    u32 fmdmccqvr2;
    u32 fmdmcqvr3;
    u32 fmdmcqvr4;
    u32 fmdmcqvr5;
    u32 fmdmsefrc;
    u32 fmdmsqfrc;
    u32 fmdmssrc;
    u32 fmdmdcr;
    u32 fmdmemsr;
    u32 res005c;
    u32[32] fmdmplr;
    u32[968] res00e0;
}
```
</details>
</li>
</ul>

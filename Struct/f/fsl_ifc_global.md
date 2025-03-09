# Struct: <code>fsl_ifc_global</code>

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
struct fsl_ifc_global {
    __be32 ifc_rev;
    u32[2] res1;
    struct (anon)[8] cspr_cs;
    u32[13] res3;
    struct (anon)[8] amask_cs;
    u32[12] res5;
    struct (anon)[8] csor_cs;
    u32[12] res7;
    struct (anon)[8] ftim_cs;
    u32[48] res9;
    __be32 rb_stat;
    __be32 rb_map;
    __be32 wb_map;
    __be32 ifc_gcr;
    u32[2] res10;
    __be32 cm_evter_stat;
    u32[2] res11;
    __be32 cm_evter_en;
    u32[2] res12;
    __be32 cm_evter_intr_en;
    u32[2] res13;
    __be32 cm_erattr0;
    __be32 cm_erattr1;
    u32[2] res14;
    __be32 ifc_ccr;
    __be32 ifc_csr;
    __be32 ddr_ccr_low;
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
struct fsl_ifc_global {
    __be32 ifc_rev;
    u32[2] res1;
    struct (anon)[8] cspr_cs;
    u32[13] res3;
    struct (anon)[8] amask_cs;
    u32[12] res5;
    struct (anon)[8] csor_cs;
    u32[12] res7;
    struct (anon)[8] ftim_cs;
    u32[48] res9;
    __be32 rb_stat;
    __be32 rb_map;
    __be32 wb_map;
    __be32 ifc_gcr;
    u32[2] res10;
    __be32 cm_evter_stat;
    u32[2] res11;
    __be32 cm_evter_en;
    u32[2] res12;
    __be32 cm_evter_intr_en;
    u32[2] res13;
    __be32 cm_erattr0;
    __be32 cm_erattr1;
    u32[2] res14;
    __be32 ifc_ccr;
    __be32 ifc_csr;
    __be32 ddr_ccr_low;
}
```
</details>
</li>
</ul>

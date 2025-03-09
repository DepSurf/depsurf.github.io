# Struct: <code>mtk_eint_regs</code>

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
struct mtk_eint_regs {
    unsigned int stat;
    unsigned int ack;
    unsigned int mask;
    unsigned int mask_set;
    unsigned int mask_clr;
    unsigned int sens;
    unsigned int sens_set;
    unsigned int sens_clr;
    unsigned int soft;
    unsigned int soft_set;
    unsigned int soft_clr;
    unsigned int pol;
    unsigned int pol_set;
    unsigned int pol_clr;
    unsigned int dom_en;
    unsigned int dbnc_ctrl;
    unsigned int dbnc_set;
    unsigned int dbnc_clr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mtk_eint_regs {
    unsigned int stat;
    unsigned int ack;
    unsigned int mask;
    unsigned int mask_set;
    unsigned int mask_clr;
    unsigned int sens;
    unsigned int sens_set;
    unsigned int sens_clr;
    unsigned int soft;
    unsigned int soft_set;
    unsigned int soft_clr;
    unsigned int pol;
    unsigned int pol_set;
    unsigned int pol_clr;
    unsigned int dom_en;
    unsigned int dbnc_ctrl;
    unsigned int dbnc_set;
    unsigned int dbnc_clr;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct mtk_eint_regs {
    unsigned int stat;
    unsigned int ack;
    unsigned int mask;
    unsigned int mask_set;
    unsigned int mask_clr;
    unsigned int sens;
    unsigned int sens_set;
    unsigned int sens_clr;
    unsigned int soft;
    unsigned int soft_set;
    unsigned int soft_clr;
    unsigned int pol;
    unsigned int pol_set;
    unsigned int pol_clr;
    unsigned int dom_en;
    unsigned int dbnc_ctrl;
    unsigned int dbnc_set;
    unsigned int dbnc_clr;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct mtk_eint_regs {
    unsigned int stat;
    unsigned int ack;
    unsigned int mask;
    unsigned int mask_set;
    unsigned int mask_clr;
    unsigned int sens;
    unsigned int sens_set;
    unsigned int sens_clr;
    unsigned int soft;
    unsigned int soft_set;
    unsigned int soft_clr;
    unsigned int pol;
    unsigned int pol_set;
    unsigned int pol_clr;
    unsigned int dom_en;
    unsigned int dbnc_ctrl;
    unsigned int dbnc_set;
    unsigned int dbnc_clr;
}
```
</details>
</li>
</ul>

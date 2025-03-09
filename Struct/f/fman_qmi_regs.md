# Struct: <code>fman_qmi_regs</code>

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
struct fman_qmi_regs {
    u32 fmqm_gc;
    u32 res0004;
    u32 fmqm_eie;
    u32 fmqm_eien;
    u32 fmqm_eif;
    u32 fmqm_ie;
    u32 fmqm_ien;
    u32 fmqm_if;
    u32 fmqm_gs;
    u32 fmqm_ts;
    u32 fmqm_etfc;
    u32 fmqm_dtfc;
    u32 fmqm_dc0;
    u32 fmqm_dc1;
    u32 fmqm_dc2;
    u32 fmqm_dc3;
    u32 fmqm_dfdc;
    u32 fmqm_dfcc;
    u32 fmqm_dffc;
    u32 fmqm_dcc;
    u32[7] res0050;
    u32 fmqm_tapc;
    u32 fmqm_dmcvc;
    u32 fmqm_difdcc;
    u32 fmqm_da1v;
    u32 res007c;
    u32 fmqm_dtc;
    u32 fmqm_efddd;
    u32[2] res0088;
    struct (anon)[3] dbg_traps;
    u8[784] res00f0;
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
struct fman_qmi_regs {
    u32 fmqm_gc;
    u32 res0004;
    u32 fmqm_eie;
    u32 fmqm_eien;
    u32 fmqm_eif;
    u32 fmqm_ie;
    u32 fmqm_ien;
    u32 fmqm_if;
    u32 fmqm_gs;
    u32 fmqm_ts;
    u32 fmqm_etfc;
    u32 fmqm_dtfc;
    u32 fmqm_dc0;
    u32 fmqm_dc1;
    u32 fmqm_dc2;
    u32 fmqm_dc3;
    u32 fmqm_dfdc;
    u32 fmqm_dfcc;
    u32 fmqm_dffc;
    u32 fmqm_dcc;
    u32[7] res0050;
    u32 fmqm_tapc;
    u32 fmqm_dmcvc;
    u32 fmqm_difdcc;
    u32 fmqm_da1v;
    u32 res007c;
    u32 fmqm_dtc;
    u32 fmqm_efddd;
    u32[2] res0088;
    struct (anon)[3] dbg_traps;
    u8[784] res00f0;
}
```
</details>
</li>
</ul>

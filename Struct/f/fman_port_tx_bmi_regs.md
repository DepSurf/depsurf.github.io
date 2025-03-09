# Struct: <code>fman_port_tx_bmi_regs</code>

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
struct fman_port_tx_bmi_regs {
    u32 fmbm_tcfg;
    u32 fmbm_tst;
    u32 fmbm_tda;
    u32 fmbm_tfp;
    u32 fmbm_tfed;
    u32 fmbm_ticp;
    u32 fmbm_tfdne;
    u32 fmbm_tfca;
    u32 fmbm_tcfqid;
    u32 fmbm_tefqid;
    u32 fmbm_tfene;
    u32 fmbm_trlmts;
    u32 fmbm_trlmt;
    u32[14] reserved0034;
    u32 fmbm_tccb;
    u32 fmbm_tfne;
    u32[2] fmbm_tpfcm;
    u32 fmbm_tcmne;
    u32[96] reserved0080;
    u32 fmbm_tstc;
    u32 fmbm_tfrc;
    u32 fmbm_tfdc;
    u32 fmbm_tfledc;
    u32 fmbm_tfufdc;
    u32 fmbm_tbdc;
    u32[26] reserved0218;
    u32 fmbm_tpc;
    u32 fmbm_tpcp;
    u32 fmbm_tccn;
    u32 fmbm_ttuc;
    u32 fmbm_ttcquc;
    u32 fmbm_tduc;
    u32 fmbm_tfuc;
    u32[16] reserved029c;
    u32[3] fmbm_tdcfg;
    u32 fmbm_tgpr;
    u32[58] reserved0310;
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
struct fman_port_tx_bmi_regs {
    u32 fmbm_tcfg;
    u32 fmbm_tst;
    u32 fmbm_tda;
    u32 fmbm_tfp;
    u32 fmbm_tfed;
    u32 fmbm_ticp;
    u32 fmbm_tfdne;
    u32 fmbm_tfca;
    u32 fmbm_tcfqid;
    u32 fmbm_tefqid;
    u32 fmbm_tfene;
    u32 fmbm_trlmts;
    u32 fmbm_trlmt;
    u32[14] reserved0034;
    u32 fmbm_tccb;
    u32 fmbm_tfne;
    u32[2] fmbm_tpfcm;
    u32 fmbm_tcmne;
    u32[96] reserved0080;
    u32 fmbm_tstc;
    u32 fmbm_tfrc;
    u32 fmbm_tfdc;
    u32 fmbm_tfledc;
    u32 fmbm_tfufdc;
    u32 fmbm_tbdc;
    u32[26] reserved0218;
    u32 fmbm_tpc;
    u32 fmbm_tpcp;
    u32 fmbm_tccn;
    u32 fmbm_ttuc;
    u32 fmbm_ttcquc;
    u32 fmbm_tduc;
    u32 fmbm_tfuc;
    u32[16] reserved029c;
    u32[3] fmbm_tdcfg;
    u32 fmbm_tgpr;
    u32[58] reserved0310;
}
```
</details>
</li>
</ul>

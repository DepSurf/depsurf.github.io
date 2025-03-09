# Struct: <code>fman_port_rx_bmi_regs</code>

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
struct fman_port_rx_bmi_regs {
    u32 fmbm_rcfg;
    u32 fmbm_rst;
    u32 fmbm_rda;
    u32 fmbm_rfp;
    u32 fmbm_rfed;
    u32 fmbm_ricp;
    u32 fmbm_rim;
    u32 fmbm_rebm;
    u32 fmbm_rfne;
    u32 fmbm_rfca;
    u32 fmbm_rfpne;
    u32 fmbm_rpso;
    u32 fmbm_rpp;
    u32 fmbm_rccb;
    u32 fmbm_reth;
    u32[1] reserved003c;
    u32[8] fmbm_rprai;
    u32 fmbm_rfqid;
    u32 fmbm_refqid;
    u32 fmbm_rfsdm;
    u32 fmbm_rfsem;
    u32 fmbm_rfene;
    u32[2] reserved0074;
    u32 fmbm_rcmne;
    u32[32] reserved0080;
    u32[8] fmbm_ebmpi;
    u32[8] fmbm_acnt;
    u32[8] reserved0130;
    u32[8] fmbm_rcgm;
    u32 fmbm_mpd;
    u32[31] reserved0184;
    u32 fmbm_rstc;
    u32 fmbm_rfrc;
    u32 fmbm_rfbc;
    u32 fmbm_rlfc;
    u32 fmbm_rffc;
    u32 fmbm_rfdc;
    u32 fmbm_rfldec;
    u32 fmbm_rodc;
    u32 fmbm_rbdc;
    u32 fmbm_rpec;
    u32[22] reserved0224;
    u32 fmbm_rpc;
    u32 fmbm_rpcp;
    u32 fmbm_rccn;
    u32 fmbm_rtuc;
    u32 fmbm_rrquc;
    u32 fmbm_rduc;
    u32 fmbm_rfuc;
    u32 fmbm_rpac;
    u32[24] reserved02a0;
    u32[3] fmbm_rdcfg;
    u32 fmbm_rgpr;
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
struct fman_port_rx_bmi_regs {
    u32 fmbm_rcfg;
    u32 fmbm_rst;
    u32 fmbm_rda;
    u32 fmbm_rfp;
    u32 fmbm_rfed;
    u32 fmbm_ricp;
    u32 fmbm_rim;
    u32 fmbm_rebm;
    u32 fmbm_rfne;
    u32 fmbm_rfca;
    u32 fmbm_rfpne;
    u32 fmbm_rpso;
    u32 fmbm_rpp;
    u32 fmbm_rccb;
    u32 fmbm_reth;
    u32[1] reserved003c;
    u32[8] fmbm_rprai;
    u32 fmbm_rfqid;
    u32 fmbm_refqid;
    u32 fmbm_rfsdm;
    u32 fmbm_rfsem;
    u32 fmbm_rfene;
    u32[2] reserved0074;
    u32 fmbm_rcmne;
    u32[32] reserved0080;
    u32[8] fmbm_ebmpi;
    u32[8] fmbm_acnt;
    u32[8] reserved0130;
    u32[8] fmbm_rcgm;
    u32 fmbm_mpd;
    u32[31] reserved0184;
    u32 fmbm_rstc;
    u32 fmbm_rfrc;
    u32 fmbm_rfbc;
    u32 fmbm_rlfc;
    u32 fmbm_rffc;
    u32 fmbm_rfdc;
    u32 fmbm_rfldec;
    u32 fmbm_rodc;
    u32 fmbm_rbdc;
    u32 fmbm_rpec;
    u32[22] reserved0224;
    u32 fmbm_rpc;
    u32 fmbm_rpcp;
    u32 fmbm_rccn;
    u32 fmbm_rtuc;
    u32 fmbm_rrquc;
    u32 fmbm_rduc;
    u32 fmbm_rfuc;
    u32 fmbm_rpac;
    u32[24] reserved02a0;
    u32[3] fmbm_rdcfg;
    u32 fmbm_rgpr;
    u32[58] reserved0310;
}
```
</details>
</li>
</ul>

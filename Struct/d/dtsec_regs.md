# Struct: <code>dtsec_regs</code>

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
struct dtsec_regs {
    u32 tsec_id;
    u32 tsec_id2;
    u32 ievent;
    u32 imask;
    u32[1] reserved0010;
    u32 ecntrl;
    u32 ptv;
    u32 tbipa;
    u32 tmr_ctrl;
    u32 tmr_pevent;
    u32 tmr_pemask;
    u32[5] reserved002c;
    u32 tctrl;
    u32[3] reserved0044;
    u32 rctrl;
    u32[11] reserved0054;
    u32[8] igaddr;
    u32[8] gaddr;
    u32[16] reserved00c0;
    u32 maccfg1;
    u32 maccfg2;
    u32 ipgifg;
    u32 hafdup;
    u32 maxfrm;
    u32[10] reserved0114;
    u32 ifstat;
    u32 macstnaddr1;
    u32 macstnaddr2;
    struct (anon)[15] macaddr;
    u32[16] reserved01c0;
    u32 tr64;
    u32 tr127;
    u32 tr255;
    u32 tr511;
    u32 tr1k;
    u32 trmax;
    u32 trmgv;
    u32 rbyt;
    u32 rpkt;
    u32 rfcs;
    u32 rmca;
    u32 rbca;
    u32 rxcf;
    u32 rxpf;
    u32 rxuo;
    u32 raln;
    u32 rflr;
    u32 rcde;
    u32 rcse;
    u32 rund;
    u32 rovr;
    u32 rfrg;
    u32 rjbr;
    u32 rdrp;
    u32 tbyt;
    u32 tpkt;
    u32 tmca;
    u32 tbca;
    u32 txpf;
    u32 tdfr;
    u32 tedf;
    u32 tscl;
    u32 tmcl;
    u32 tlcl;
    u32 txcl;
    u32 tncl;
    u32[1] reserved0290;
    u32 tdrp;
    u32 tjbr;
    u32 tfcs;
    u32 txcf;
    u32 tovr;
    u32 tund;
    u32 tfrg;
    u32 car1;
    u32 car2;
    u32 cam1;
    u32 cam2;
    u32[848] reserved02c0;
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
struct dtsec_regs {
    u32 tsec_id;
    u32 tsec_id2;
    u32 ievent;
    u32 imask;
    u32[1] reserved0010;
    u32 ecntrl;
    u32 ptv;
    u32 tbipa;
    u32 tmr_ctrl;
    u32 tmr_pevent;
    u32 tmr_pemask;
    u32[5] reserved002c;
    u32 tctrl;
    u32[3] reserved0044;
    u32 rctrl;
    u32[11] reserved0054;
    u32[8] igaddr;
    u32[8] gaddr;
    u32[16] reserved00c0;
    u32 maccfg1;
    u32 maccfg2;
    u32 ipgifg;
    u32 hafdup;
    u32 maxfrm;
    u32[10] reserved0114;
    u32 ifstat;
    u32 macstnaddr1;
    u32 macstnaddr2;
    struct (anon)[15] macaddr;
    u32[16] reserved01c0;
    u32 tr64;
    u32 tr127;
    u32 tr255;
    u32 tr511;
    u32 tr1k;
    u32 trmax;
    u32 trmgv;
    u32 rbyt;
    u32 rpkt;
    u32 rfcs;
    u32 rmca;
    u32 rbca;
    u32 rxcf;
    u32 rxpf;
    u32 rxuo;
    u32 raln;
    u32 rflr;
    u32 rcde;
    u32 rcse;
    u32 rund;
    u32 rovr;
    u32 rfrg;
    u32 rjbr;
    u32 rdrp;
    u32 tbyt;
    u32 tpkt;
    u32 tmca;
    u32 tbca;
    u32 txpf;
    u32 tdfr;
    u32 tedf;
    u32 tscl;
    u32 tmcl;
    u32 tlcl;
    u32 txcl;
    u32 tncl;
    u32[1] reserved0290;
    u32 tdrp;
    u32 tjbr;
    u32 tfcs;
    u32 txcf;
    u32 tovr;
    u32 tund;
    u32 tfrg;
    u32 car1;
    u32 car2;
    u32 cam1;
    u32 cam2;
    u32[848] reserved02c0;
}
```
</details>
</li>
</ul>

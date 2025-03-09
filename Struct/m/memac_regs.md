# Struct: <code>memac_regs</code>

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
struct memac_regs {
    u32[2] res0000;
    u32 command_config;
    struct mac_addr mac_addr0;
    u32 maxfrm;
    u32[1] res0018;
    u32 rx_fifo_sections;
    u32 tx_fifo_sections;
    u32[2] res0024;
    u32 hashtable_ctrl;
    u32[4] res0030;
    u32 ievent;
    u32 tx_ipg_length;
    u32 res0048;
    u32 imask;
    u32 res0050;
    u32[4] pause_quanta;
    u32[4] pause_thresh;
    u32 rx_pause_status;
    u32[2] res0078;
    struct mac_addr[7] mac_addr;
    u32 lpwake_timer;
    u32 sleep_timer;
    u32[8] res00c0;
    u32 statn_config;
    u32[7] res00e4;
    u32 reoct_l;
    u32 reoct_u;
    u32 roct_l;
    u32 roct_u;
    u32 raln_l;
    u32 raln_u;
    u32 rxpf_l;
    u32 rxpf_u;
    u32 rfrm_l;
    u32 rfrm_u;
    u32 rfcs_l;
    u32 rfcs_u;
    u32 rvlan_l;
    u32 rvlan_u;
    u32 rerr_l;
    u32 rerr_u;
    u32 ruca_l;
    u32 ruca_u;
    u32 rmca_l;
    u32 rmca_u;
    u32 rbca_l;
    u32 rbca_u;
    u32 rdrp_l;
    u32 rdrp_u;
    u32 rpkt_l;
    u32 rpkt_u;
    u32 rund_l;
    u32 rund_u;
    u32 r64_l;
    u32 r64_u;
    u32 r127_l;
    u32 r127_u;
    u32 r255_l;
    u32 r255_u;
    u32 r511_l;
    u32 r511_u;
    u32 r1023_l;
    u32 r1023_u;
    u32 r1518_l;
    u32 r1518_u;
    u32 r1519x_l;
    u32 r1519x_u;
    u32 rovr_l;
    u32 rovr_u;
    u32 rjbr_l;
    u32 rjbr_u;
    u32 rfrg_l;
    u32 rfrg_u;
    u32 rcnp_l;
    u32 rcnp_u;
    u32 rdrntp_l;
    u32 rdrntp_u;
    u32[12] res01d0;
    u32 teoct_l;
    u32 teoct_u;
    u32 toct_l;
    u32 toct_u;
    u32[2] res0210;
    u32 txpf_l;
    u32 txpf_u;
    u32 tfrm_l;
    u32 tfrm_u;
    u32 tfcs_l;
    u32 tfcs_u;
    u32 tvlan_l;
    u32 tvlan_u;
    u32 terr_l;
    u32 terr_u;
    u32 tuca_l;
    u32 tuca_u;
    u32 tmca_l;
    u32 tmca_u;
    u32 tbca_l;
    u32 tbca_u;
    u32[2] res0258;
    u32 tpkt_l;
    u32 tpkt_u;
    u32 tund_l;
    u32 tund_u;
    u32 t64_l;
    u32 t64_u;
    u32 t127_l;
    u32 t127_u;
    u32 t255_l;
    u32 t255_u;
    u32 t511_l;
    u32 t511_u;
    u32 t1023_l;
    u32 t1023_u;
    u32 t1518_l;
    u32 t1518_u;
    u32 t1519x_l;
    u32 t1519x_u;
    u32[6] res02a8;
    u32 tcnp_l;
    u32 tcnp_u;
    u32[14] res02c8;
    u32 if_mode;
    u32 if_status;
    u32[14] res0308;
    u32 hg_config;
    u32[3] res0344;
    u32 hg_pause_quanta;
    u32[3] res0354;
    u32 hg_pause_thresh;
    u32[3] res0364;
    u32 hgrx_pause_status;
    u32 hg_fifos_status;
    u32 rhm;
    u32 thm;
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
struct memac_regs {
    u32[2] res0000;
    u32 command_config;
    struct mac_addr mac_addr0;
    u32 maxfrm;
    u32[1] res0018;
    u32 rx_fifo_sections;
    u32 tx_fifo_sections;
    u32[2] res0024;
    u32 hashtable_ctrl;
    u32[4] res0030;
    u32 ievent;
    u32 tx_ipg_length;
    u32 res0048;
    u32 imask;
    u32 res0050;
    u32[4] pause_quanta;
    u32[4] pause_thresh;
    u32 rx_pause_status;
    u32[2] res0078;
    struct mac_addr[7] mac_addr;
    u32 lpwake_timer;
    u32 sleep_timer;
    u32[8] res00c0;
    u32 statn_config;
    u32[7] res00e4;
    u32 reoct_l;
    u32 reoct_u;
    u32 roct_l;
    u32 roct_u;
    u32 raln_l;
    u32 raln_u;
    u32 rxpf_l;
    u32 rxpf_u;
    u32 rfrm_l;
    u32 rfrm_u;
    u32 rfcs_l;
    u32 rfcs_u;
    u32 rvlan_l;
    u32 rvlan_u;
    u32 rerr_l;
    u32 rerr_u;
    u32 ruca_l;
    u32 ruca_u;
    u32 rmca_l;
    u32 rmca_u;
    u32 rbca_l;
    u32 rbca_u;
    u32 rdrp_l;
    u32 rdrp_u;
    u32 rpkt_l;
    u32 rpkt_u;
    u32 rund_l;
    u32 rund_u;
    u32 r64_l;
    u32 r64_u;
    u32 r127_l;
    u32 r127_u;
    u32 r255_l;
    u32 r255_u;
    u32 r511_l;
    u32 r511_u;
    u32 r1023_l;
    u32 r1023_u;
    u32 r1518_l;
    u32 r1518_u;
    u32 r1519x_l;
    u32 r1519x_u;
    u32 rovr_l;
    u32 rovr_u;
    u32 rjbr_l;
    u32 rjbr_u;
    u32 rfrg_l;
    u32 rfrg_u;
    u32 rcnp_l;
    u32 rcnp_u;
    u32 rdrntp_l;
    u32 rdrntp_u;
    u32[12] res01d0;
    u32 teoct_l;
    u32 teoct_u;
    u32 toct_l;
    u32 toct_u;
    u32[2] res0210;
    u32 txpf_l;
    u32 txpf_u;
    u32 tfrm_l;
    u32 tfrm_u;
    u32 tfcs_l;
    u32 tfcs_u;
    u32 tvlan_l;
    u32 tvlan_u;
    u32 terr_l;
    u32 terr_u;
    u32 tuca_l;
    u32 tuca_u;
    u32 tmca_l;
    u32 tmca_u;
    u32 tbca_l;
    u32 tbca_u;
    u32[2] res0258;
    u32 tpkt_l;
    u32 tpkt_u;
    u32 tund_l;
    u32 tund_u;
    u32 t64_l;
    u32 t64_u;
    u32 t127_l;
    u32 t127_u;
    u32 t255_l;
    u32 t255_u;
    u32 t511_l;
    u32 t511_u;
    u32 t1023_l;
    u32 t1023_u;
    u32 t1518_l;
    u32 t1518_u;
    u32 t1519x_l;
    u32 t1519x_u;
    u32[6] res02a8;
    u32 tcnp_l;
    u32 tcnp_u;
    u32[14] res02c8;
    u32 if_mode;
    u32 if_status;
    u32[14] res0308;
    u32 hg_config;
    u32[3] res0344;
    u32 hg_pause_quanta;
    u32[3] res0354;
    u32 hg_pause_thresh;
    u32[3] res0364;
    u32 hgrx_pause_status;
    u32 hg_fifos_status;
    u32 rhm;
    u32 thm;
}
```
</details>
</li>
</ul>

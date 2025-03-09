# Struct: <code>tgec_regs</code>

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
struct tgec_regs {
    u32 tgec_id;
    u32[1] reserved001;
    u32 command_config;
    u32 mac_addr_0;
    u32 mac_addr_1;
    u32 maxfrm;
    u32 pause_quant;
    u32 rx_fifo_sections;
    u32 tx_fifo_sections;
    u32 rx_fifo_almost_f_e;
    u32 tx_fifo_almost_f_e;
    u32 hashtable_ctrl;
    u32 mdio_cfg_status;
    u32 mdio_command;
    u32 mdio_data;
    u32 mdio_regaddr;
    u32 status;
    u32 tx_ipg_len;
    u32 mac_addr_2;
    u32 mac_addr_3;
    u32 rx_fifo_ptr_rd;
    u32 rx_fifo_ptr_wr;
    u32 tx_fifo_ptr_rd;
    u32 tx_fifo_ptr_wr;
    u32 imask;
    u32 ievent;
    u32 udp_port;
    u32 type_1588v2;
    u32[4] reserved070;
    u32 tfrm_u;
    u32 tfrm_l;
    u32 rfrm_u;
    u32 rfrm_l;
    u32 rfcs_u;
    u32 rfcs_l;
    u32 raln_u;
    u32 raln_l;
    u32 txpf_u;
    u32 txpf_l;
    u32 rxpf_u;
    u32 rxpf_l;
    u32 rlong_u;
    u32 rlong_l;
    u32 rflr_u;
    u32 rflr_l;
    u32 tvlan_u;
    u32 tvlan_l;
    u32 rvlan_u;
    u32 rvlan_l;
    u32 toct_u;
    u32 toct_l;
    u32 roct_u;
    u32 roct_l;
    u32 ruca_u;
    u32 ruca_l;
    u32 rmca_u;
    u32 rmca_l;
    u32 rbca_u;
    u32 rbca_l;
    u32 terr_u;
    u32 terr_l;
    u32[2] reserved100;
    u32 tuca_u;
    u32 tuca_l;
    u32 tmca_u;
    u32 tmca_l;
    u32 tbca_u;
    u32 tbca_l;
    u32 rdrp_u;
    u32 rdrp_l;
    u32 reoct_u;
    u32 reoct_l;
    u32 rpkt_u;
    u32 rpkt_l;
    u32 trund_u;
    u32 trund_l;
    u32 r64_u;
    u32 r64_l;
    u32 r127_u;
    u32 r127_l;
    u32 r255_u;
    u32 r255_l;
    u32 r511_u;
    u32 r511_l;
    u32 r1023_u;
    u32 r1023_l;
    u32 r1518_u;
    u32 r1518_l;
    u32 r1519x_u;
    u32 r1519x_l;
    u32 trovr_u;
    u32 trovr_l;
    u32 trjbr_u;
    u32 trjbr_l;
    u32 trfrg_u;
    u32 trfrg_l;
    u32 rerr_u;
    u32 rerr_l;
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
struct tgec_regs {
    u32 tgec_id;
    u32[1] reserved001;
    u32 command_config;
    u32 mac_addr_0;
    u32 mac_addr_1;
    u32 maxfrm;
    u32 pause_quant;
    u32 rx_fifo_sections;
    u32 tx_fifo_sections;
    u32 rx_fifo_almost_f_e;
    u32 tx_fifo_almost_f_e;
    u32 hashtable_ctrl;
    u32 mdio_cfg_status;
    u32 mdio_command;
    u32 mdio_data;
    u32 mdio_regaddr;
    u32 status;
    u32 tx_ipg_len;
    u32 mac_addr_2;
    u32 mac_addr_3;
    u32 rx_fifo_ptr_rd;
    u32 rx_fifo_ptr_wr;
    u32 tx_fifo_ptr_rd;
    u32 tx_fifo_ptr_wr;
    u32 imask;
    u32 ievent;
    u32 udp_port;
    u32 type_1588v2;
    u32[4] reserved070;
    u32 tfrm_u;
    u32 tfrm_l;
    u32 rfrm_u;
    u32 rfrm_l;
    u32 rfcs_u;
    u32 rfcs_l;
    u32 raln_u;
    u32 raln_l;
    u32 txpf_u;
    u32 txpf_l;
    u32 rxpf_u;
    u32 rxpf_l;
    u32 rlong_u;
    u32 rlong_l;
    u32 rflr_u;
    u32 rflr_l;
    u32 tvlan_u;
    u32 tvlan_l;
    u32 rvlan_u;
    u32 rvlan_l;
    u32 toct_u;
    u32 toct_l;
    u32 roct_u;
    u32 roct_l;
    u32 ruca_u;
    u32 ruca_l;
    u32 rmca_u;
    u32 rmca_l;
    u32 rbca_u;
    u32 rbca_l;
    u32 terr_u;
    u32 terr_l;
    u32[2] reserved100;
    u32 tuca_u;
    u32 tuca_l;
    u32 tmca_u;
    u32 tmca_l;
    u32 tbca_u;
    u32 tbca_l;
    u32 rdrp_u;
    u32 rdrp_l;
    u32 reoct_u;
    u32 reoct_l;
    u32 rpkt_u;
    u32 rpkt_l;
    u32 trund_u;
    u32 trund_l;
    u32 r64_u;
    u32 r64_l;
    u32 r127_u;
    u32 r127_l;
    u32 r255_u;
    u32 r255_l;
    u32 r511_u;
    u32 r511_l;
    u32 r1023_u;
    u32 r1023_l;
    u32 r1518_u;
    u32 r1518_l;
    u32 r1519x_u;
    u32 r1519x_l;
    u32 trovr_u;
    u32 trovr_l;
    u32 trjbr_u;
    u32 trjbr_l;
    u32 trfrg_u;
    u32 trfrg_l;
    u32 rerr_u;
    u32 rerr_l;
}
```
</details>
</li>
</ul>
